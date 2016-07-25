#### Test (Fail) 77622416 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
 * [new branch]      vNext_aaladev_507 -> origin/vNext_aaladev_507
   744cc2c..eddeaba  vNext_czyzm_temp -> origin/vNext_czyzm_temp
   b1c6d83..5805f9f  vNext_jareksl_555 -> origin/vNext_jareksl_555
   6f742a4..5805f9f  vNext_jareksl_555_clean -> origin/vNext_jareksl_555_clean

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '6db488b'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 6db488b... Update after CR

```

```
-e [0;32mAndroid native UT files will be copied to the platform folder
 [0m
Cordova version:
6.1.0
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├─┬ express@4.14.0 
│ ├─┬ accepts@1.3.3 
│ │ ├─┬ mime-types@2.1.11 
│ │ │ └── mime-db@1.23.0 
│ │ └── negotiator@0.6.1 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.1 
│ ├── content-type@1.0.2 
│ ├── cookie@0.3.1 
│ ├── cookie-signature@1.0.6 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.1.0 
│ ├── encodeurl@1.0.1 
│ ├── escape-html@1.0.3 
│ ├── etag@1.7.0 
│ ├─┬ finalhandler@0.5.0 
│ │ ├── statuses@1.3.0 
│ │ └── unpipe@1.0.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.1 
│ ├── methods@1.1.2 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.1.2 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.1.1 
│ ├── qs@6.2.0 
│ ├── range-parser@1.2.0 
│ ├─┬ send@0.14.1 
│ │ ├── destroy@1.0.4 
│ │ ├─┬ http-errors@1.5.0 
│ │ │ ├── inherits@2.0.1 
│ │ │ └── setprototypeof@1.0.1 
│ │ └── mime@1.3.4 
│ ├── serve-static@1.11.1 
│ ├─┬ type-is@1.6.13 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.1.0 
├─┬ fs-extra-promise@0.2.1 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.24.0 
│   ├── graceful-fs@4.1.4 
│   ├── jsonfile@2.3.1 
│   ├── path-is-absolute@1.0.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.0.5 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.2 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       └── once@1.3.3 
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
│ └─┬ socket.io-parser@2.2.6 
│   ├── benchmark@1.0.0 
│   ├── component-emitter@1.1.2 
│   └── json3@3.3.2 
├─┬ socket.io-client@1.4.8 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.2.0 
│ ├─┬ engine.io-client@1.6.11 
│ │ ├── component-inherit@0.0.3 
│ │ ├── has-cors@1.1.0 
│ │ ├── parsejson@0.0.1 
│ │ ├── parseqs@0.0.2 
│ │ ├── ws@1.0.1 
│ │ ├── xmlhttprequest-ssl@1.5.1 
│ │ └── yeast@0.1.2 
│ ├── indexof@0.0.1 
│ ├── object-component@0.0.3 
│ ├─┬ parseuri@0.0.4 
│ │ └─┬ better-assert@1.0.2 
│ │   └── callsite@1.0.0 
│ └── to-array@0.1.4 
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
├─┬ body-parser@1.15.2 
│ ├── bytes@2.4.0 
│ ├── content-type@1.0.2 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.1.0 
│ ├─┬ http-errors@1.5.0 
│ │ ├── setprototypeof@1.0.1 
│ │ └── statuses@1.3.0 
│ ├── iconv-lite@0.4.13 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@6.2.0 
│ ├─┬ raw-body@2.1.7 
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
│ ├── depd@1.0.1 
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
│ ├── qs@4.0.0 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── depd@1.0.1 
│ │ ├── destroy@1.0.3 
│ │ ├── http-errors@1.3.1 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── destroy@1.0.4 
│ │   ├── http-errors@1.3.1 
│ │   └── statuses@1.2.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├── forever-agent@0.6.1 
├── ip@1.1.3 
├── javascript-state-machine@2.3.5 
├─┬ jsdoc@3.4.0 
│ ├── async@1.4.2 
│ ├── bluebird@2.9.34 
│ ├─┬ catharsis@0.8.8 
│ │ └─┬ underscore-contrib@0.3.0 
│ │   └── underscore@1.6.0 
│ ├── escape-string-regexp@1.0.5 
│ ├── espree@2.2.5 
│ ├── js2xmlparser@1.0.0 
│ ├── marked@0.3.5 
│ ├─┬ requizzle@0.2.1 
│ │ └── underscore@1.6.0 
│ ├── strip-json-comments@1.0.4 
│ ├── taffydb@2.6.2 
│ ├── underscore@1.8.3 
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
│ │ │ │ ├── graceful-fs@4.1.4 
│ │ │ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ │ └── minimist@0.0.8 
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
├── long@3.2.0 
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
├─┬ request@2.74.0 
│ ├── aws-sign2@0.6.0 
│ ├── aws4@1.4.1 
│ ├─┬ bl@1.1.2 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
│ ├─┬ har-validator@2.0.6 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ ├─┬ is-my-json-valid@2.13.1 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ └── is-property@1.0.2 
│ │ │ └── jsonpointer@2.0.0 
│ │ └─┬ pinkie-promise@2.0.1 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.3.0 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.2 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.8.3 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.0 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.11 
│ │ └── mime-db@1.23.0 
│ ├── oauth-sign@0.8.2 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.0 
│ └── tunnel-agent@0.4.3 
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

thali@2.1.0 /Users/thali/Github/Thali_CordovaPlugin/thali
└─┬ request@2.74.0
  └─┬ http-signature@1.1.1
    └─┬ sshpk@1.8.3
      ├── ecc-jsbn@0.1.1 
      ├── jodid25519@1.0.2 
      ├── jsbn@0.1.0 
      └── tweetnacl@0.13.3 

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├─┬ fs-extra-promise@0.2.1 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.24.0 
│   ├── graceful-fs@4.1.4 
│   ├── jsonfile@2.3.1 
│   ├── path-is-absolute@1.0.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.0.5 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.2 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       └── once@1.3.3 
├─┬ jxc@1.0.15 
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
├─┬ request@2.74.0 
│ ├── aws-sign2@0.6.0 
│ ├── aws4@1.4.1 
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
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
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
│ │ ├─┬ is-my-json-valid@2.13.1 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ └── is-property@1.0.2 
│ │ │ └── jsonpointer@2.0.0 
│ │ └─┬ pinkie-promise@2.0.1 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.3.0 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.2 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.8.3 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.0 
│ │   │ └── assert-plus@1.0.0 
│ │   ├── ecc-jsbn@0.1.1 
│ │   ├─┬ getpass@0.1.6 
│ │   │ └── assert-plus@1.0.0 
│ │   ├── jodid25519@1.0.2 
│ │   ├── jsbn@0.1.0 
│ │   └── tweetnacl@0.13.3 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.11 
│ │ └── mime-db@1.23.0 
│ ├── node-uuid@1.4.7 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.1 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.0 
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
├── balanced-match@0.2.1 
├── bn.js@4.11.5 
├─┬ body-parser@1.15.2 
│ ├── bytes@2.4.0 
│ ├── content-type@1.0.2 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.1.0 
│ ├─┬ http-errors@1.5.0 
│ │ ├── setprototypeof@1.0.1 
│ │ └── statuses@1.3.0 
│ ├── iconv-lite@0.4.13 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@6.2.0 
│ ├─┬ raw-body@2.1.7 
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
│ ├── depd@1.0.1 
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
│ ├── qs@4.0.0 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── depd@1.0.1 
│ │ ├── destroy@1.0.3 
│ │ ├── http-errors@1.3.1 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── destroy@1.0.4 
│ │   ├── http-errors@1.3.1 
│ │   └── statuses@1.2.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ express-pouchdb@1.0.6 
│ ├── basic-auth@1.0.4 
│ ├── bluebird@3.4.1 
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
│ │ └── stream-counter@0.2.0 
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
│ │ ├── pouchdb-extend@0.1.2 
│ │ ├─┬ pouchdb-promise@5.4.0 
│ │ │ └─┬ lie@3.0.4 
│ │ │   ├─┬ es3ify@0.2.2 
│ │ │   │ ├── esprima@2.7.2 
│ │ │   │ └─┬ jstransform@11.0.3 
│ │ │   │   ├── base62@1.1.1 
│ │ │   │   ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │   │   └── source-map@0.4.4 
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
├─┬ fs-extra-promise@0.2.1 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.24.0 
│   ├── graceful-fs@4.1.4 
│   ├── jsonfile@2.3.1 
│   ├── path-is-absolute@1.0.0 
│   └─┬ rimraf@2.5.4 
│     └── glob@7.0.5 
├── is-property@1.0.2 
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
│ │   │ ├── detective@4.3.1 
│ │   │ ├── glob@5.0.15 
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
├── long@3.2.0 
├── minimist@1.2.0 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.5 
│ │ ├── end-of-stream@1.0.0 
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
├─┬ nock@2.18.2 
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
│ │ ├── abstract-leveldown@2.6.0 
│ │ ├── functional-red-black-tree@1.0.1 
│ │ └── ltgt@1.0.2 
│ ├── pouchdb-collate@1.2.0 
│ ├── pouchdb-collections@1.0.1 
│ ├─┬ request@2.72.0 
│ │ ├── extend@3.0.0 
│ │ ├── qs@6.1.0 
│ │ └── tough-cookie@2.2.2 
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
├─┬ proxyquire@1.7.10 
│ ├─┬ fill-keys@1.0.2 
│ │ └── is-object@1.0.1 
│ ├── module-not-found-error@1.0.1 
│ └── resolve@1.1.7 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.74.0 
│ ├── aws-sign2@0.6.0 
│ ├── aws4@1.4.1 
│ ├─┬ bl@1.1.2 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
│ ├─┬ har-validator@2.0.6 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ ├─┬ is-my-json-valid@2.13.1 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├── generate-object-property@1.2.0 
│ │ │ └── jsonpointer@2.0.0 
│ │ └─┬ pinkie-promise@2.0.1 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.3.0 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.2 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.8.3 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.0 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.11 
│ │ └── mime-db@1.23.0 
│ ├── oauth-sign@0.8.2 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.0 
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
├─┬ sinon@1.17.4 
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
│ ├─┬ has-binary@0.1.7 
│ │ └── isarray@0.0.1 
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
├─┬ supertest@1.2.0 
│ └─┬ superagent@1.8.3 
│   ├── cookiejar@2.0.6 
│   ├── extend@3.0.0 
│   ├── form-data@1.0.0-rc3 
│   ├── formidable@1.0.17 
│   ├── qs@2.3.3 
│   ├── readable-stream@1.0.27-1 
│   └── reduce-component@1.0.1 
├─┬ supertest-as-promised@2.0.2 
│ └── bluebird@2.10.2 
├─┬ tape@4.6.0 
│ ├── defined@1.0.0 
│ ├── function-bind@1.1.0 
│ ├─┬ glob@7.0.5 
│ │ ├── fs.realpath@1.0.0 
│ │ ├─┬ inflight@1.0.5 
│ │ │ └── wrappy@1.0.2 
│ │ ├─┬ minimatch@3.0.2 
│ │ │ └─┬ brace-expansion@1.1.6 
│ │ │   └── balanced-match@0.4.2 
│ │ └── once@1.3.3 
│ ├── has@1.0.1 
│ ├── object-inspect@1.2.1 
│ ├── resumer@0.0.0 
│ ├─┬ string.prototype.trim@1.1.2 
│ │ ├── define-properties@1.1.2 
│ │ └─┬ es-abstract@1.5.1 
│ │   ├─┬ es-to-primitive@1.1.1 
│ │   │ ├── is-date-object@1.0.1 
│ │   │ └── is-symbol@1.0.1 
│ │   ├── is-callable@1.1.3 
│ │   └── is-regex@1.0.3 
│ └── through@2.3.8 
├─┬ tape-catch@1.0.6 
│ └─┬ global@4.3.0 
│   ├─┬ min-document@2.18.0 
│   │ └── dom-walk@0.1.1 
│   └── process@0.5.2 
├─┬ thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
│ ├─┬ body-parser@1.15.2 
│ │ ├── bytes@2.4.0 
│ │ ├── content-type@1.0.2 
│ │ ├─┬ debug@2.2.0 
│ │ │ └── ms@0.7.1 
│ │ ├── depd@1.1.0 
│ │ ├─┬ http-errors@1.5.0 
│ │ │ ├── setprototypeof@1.0.1 
│ │ │ └── statuses@1.3.0 
│ │ ├── iconv-lite@0.4.13 
│ │ ├─┬ on-finished@2.3.0 
│ │ │ └── ee-first@1.1.1 
│ │ ├── qs@6.2.0 
│ │ ├─┬ raw-body@2.1.7 
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
│ │ ├── depd@1.0.1 
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
│ │ ├── qs@4.0.0 
│ │ ├── range-parser@1.0.3 
│ │ ├─┬ send@0.13.0 
│ │ │ ├── depd@1.0.1 
│ │ │ ├── destroy@1.0.3 
│ │ │ ├── http-errors@1.3.1 
│ │ │ ├── mime@1.3.4 
│ │ │ └── statuses@1.2.1 
│ │ ├─┬ serve-static@1.10.3 
│ │ │ ├── escape-html@1.0.3 
│ │ │ └─┬ send@0.13.2 
│ │ │   ├── destroy@1.0.4 
│ │ │   ├── http-errors@1.3.1 
│ │ │   └── statuses@1.2.1 
│ │ ├── utils-merge@1.0.0 
│ │ └── vary@1.0.1 
│ ├── forever-agent@0.6.1 
│ ├── ip@1.1.3 
│ ├─┬ jsdoc@3.4.0
│ │ └── escape-string-regexp@1.0.5 
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
│ │ │ │ │ │ ├─┬ minimatch@3.0.2 
│ │ │ │ │ │ │ └─┬ brace-expansion@1.1.6 
│ │ │ │ │ │ │   ├── balanced-match@0.4.2 
│ │ │ │ │ │ │   └── concat-map@0.0.1 
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
│ │ ├── immediate@3.0.5 
│ │ ├─┬ inline-process-browser@1.0.0 
│ │ │ ├─┬ falafel@1.2.0 
│ │ │ │ ├── acorn@1.2.2 
│ │ │ │ ├── foreach@2.0.5 
│ │ │ │ ├── isarray@0.0.1 
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
│ ├── long@3.2.0 
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
│ ├─┬ request@2.74.0 
│ │ ├── aws-sign2@0.6.0 
│ │ ├── aws4@1.4.1 
│ │ ├─┬ bl@1.1.2 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── caseless@0.11.0 
│ │ ├─┬ combined-stream@1.0.5 
│ │ │ └── delayed-stream@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ form-data@1.0.0-rc4 
│ │ │ └── async@1.5.2 
│ │ ├─┬ har-validator@2.0.6 
│ │ │ ├─┬ chalk@1.1.3 
│ │ │ │ ├── ansi-styles@2.2.1 
│ │ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ │ └── ansi-regex@2.0.0 
│ │ │ │ ├── strip-ansi@3.0.1 
│ │ │ │ └── supports-color@2.0.0 
│ │ │ ├─┬ commander@2.9.0 
│ │ │ │ └── graceful-readlink@1.0.1 
│ │ │ ├─┬ is-my-json-valid@2.13.1 
│ │ │ │ ├── generate-function@2.0.0 
│ │ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ │ └── is-property@1.0.2 
│ │ │ │ └── jsonpointer@2.0.0 
│ │ │ └─┬ pinkie-promise@2.0.1 
│ │ │   └── pinkie@2.0.4 
│ │ ├─┬ hawk@3.1.3 
│ │ │ ├── boom@2.10.1 
│ │ │ ├── cryptiles@2.0.5 
│ │ │ ├── hoek@2.16.3 
│ │ │ └── sntp@1.0.9 
│ │ ├─┬ http-signature@1.1.1 
│ │ │ ├── assert-plus@0.2.0 
│ │ │ ├─┬ jsprim@1.3.0 
│ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ ├── json-schema@0.2.2 
│ │ │ │ └── verror@1.3.6 
│ │ │ └─┬ sshpk@1.8.3 
│ │ │   ├── asn1@0.2.3 
│ │ │   ├── assert-plus@1.0.0 
│ │ │   ├─┬ dashdash@1.14.0 
│ │ │   │ └── assert-plus@1.0.0 
│ │ │   └─┬ getpass@0.1.6 
│ │ │     └── assert-plus@1.0.0 
│ │ ├── is-typedarray@1.0.0 
│ │ ├── isstream@0.1.2 
│ │ ├── json-stringify-safe@5.0.1 
│ │ ├─┬ mime-types@2.1.11 
│ │ │ └── mime-db@1.23.0 
│ │ ├── oauth-sign@0.8.2 
│ │ ├── stringstream@0.0.5 
│ │ ├── tough-cookie@2.3.0 
│ │ └── tunnel-agent@0.4.3 
│ └── urlsafe-base64@1.0.0 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.1 
├── urlsafe-base64@1.0.0 
└── uuid@2.0.2 


> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
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
DEBUG createNativeListener: listening 49892
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49894
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
DEBUG createNativeListener: listening 49897
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
DEBUG createNativeListener: listening 49901
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
DEBUG createNativeListener: listening 49906
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
DEBUG createNativeListener: listening 49910
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
DEBUG createNativeListener: listening 49914
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
DEBUG createNativeListener: listening 49918
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
DEBUG createNativeListener: listening 49922
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
DEBUG createNativeListener: listening 49974
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
DEBUG createNativeListener: listening 49978
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
DEBUG createNativeListener: listening 49983
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49986
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49989
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49993
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
DEBUG createNativeListener: listening 49998
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50002
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
DEBUG createNativeListener: listening 50011
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
DEBUG createNativeListener: listening 50020
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
DEBUG createNativeListener: listening 50026
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
DEBUG createNativeListener: listening 50033
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
DEBUG createNativeListener: listening 50038
DEBUG createPeerListener: pleaseConnect= false
ok 68 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50044
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
DEBUG createNativeListener: listening 50051
DEBUG createPeerListener: pleaseConnect= false
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createNativeListener: listening 50055
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
DEBUG createNativeListener: listening 50060
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
DEBUG createNativeListener: listening 50065
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
DEBUG createNativeListener: listening 50070
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
DEBUG createNativeListener: listening 50076
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50079
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50079
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
DEBUG createNativeListener: listening 50082
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  50085
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  50085
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
DEBUG createNativeListener: listening 50089
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50092
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50095
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50098
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50101
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50104
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50107
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50110
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50113
# teardown
# setup
# closeAll can close even when connections open
ok 97 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
ok 98 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
ok 99 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
# teardown
# setup
# enqueue and run in order
ok 100 firstPromise setTimeout
ok 101 firstPromise result
ok 102 firstPromise testValue
ok 103 secondPromise setTimeout
ok 104 secondPromise result
ok 105 secondPromise testValue
ok 106 thirdPromise in promise
ok 107 thirdPromise result
ok 108 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 109 thirdPromise - first to run
ok 110 thirdPromise - in resolve
ok 111 secondPromise - second to run
ok 112 secondPromise - in catch
ok 113 firstPromise - third to run
ok 114 firstPromise - in then
ok 115 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 116 fourth
ok 117 fourth
ok 118 second
ok 119 secondPromise - in then
ok 120 first
ok 121 firstPromise - in catch
ok 122 third
ok 123 thirdPromise - in then
ok 124 testingPromises
# teardown
# setup
# queues handled independently
ok 125 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 126 sane
# teardown
# setup
# another
ok 127 sane
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 128 specific error should be returned
# teardown
ok 129 error should be null
ok 130 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 131 specific error should be returned
# teardown
ok 132 error should be null
ok 133 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50121
ok 134 error should be null
ok 135 error should be null
ok 136 error should be null
ok 137 error should be null
# teardown
ok 138 error should be null
ok 139 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50123
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 140 error should be null
ok 141 error should be null
ok 142 error should be null
ok 143 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 144 error should be null
ok 145 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50125
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 146 error should be null
ok 147 error should be null
ok 148 error should be null
ok 149 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 150 error should be null
ok 151 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50130
ok 152 error should be null
ok 153 error should be null
ok 154 error should be null
ok 155 error should be null
# teardown
ok 156 error should be null
ok 157 error should be null
# setup
# #start should fail if called twice in a row
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50132
ok 158 first call should succeed
ok 159 first call should succeed
ok 160 specific error should be returned
# teardown
ok 161 error should be null
ok 162 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50134
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 163 called only once
ok 164 discovery state matches
ok 165 advertising state matches
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 166 error should be null
ok 167 error should be null
# setup
# does not send duplicate availability changes
ok 168 should be called once
ok 169 should not have been called more than once
# teardown
ok 170 error should be null
ok 171 error should be null
# setup
# can get the network status
ok 172 network status should have certain non-empty properties
# teardown
ok 173 error should be null
ok 174 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
ok 175 host address should match
ok 176 port should match
ok 177 host address should be null
ok 178 port should should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 179 error should be null
ok 180 error should be null
# setup
# network changes emitted correctly
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50139
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 181 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 182 wifi is on
# teardown
ok 183 error should be null
ok 184 error should be null
# setup
# network changes not emitted in stopped state
ok 185 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 186 error should be null
ok 187 error should be null
# setup
# calls correct starts when network changes
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50141
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 188 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 189 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
ok 190 startListeningForAdvertisements should have been called
ok 191 startUpdateAdvertisingAndListening should have been called
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 192 error should be null
ok 193 error should be null
# setup
# peer is marked unavailable if port number changes
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50146
ok 194 peer should have a non-empty identifier
ok 195 peer should have a non-empty host address
ok 196 peer should have port number
ok 197 peer should have suggested timeout
ok 198 peer should have a connection type
ok 199 connection type should match one of the pre-defined types
ok 200 peer should have a non-empty identifier
ok 201 host address should be null
ok 202 port number should be null
ok 203 peer should have suggested timeout
ok 204 peer should have a connection type
ok 205 connection type should match one of the pre-defined types
ok 206 port number must match
ok 207 peer should have a non-empty identifier
ok 208 peer should have a non-empty host address
ok 209 peer should have port number
ok 210 peer should have suggested timeout
ok 211 peer should have a connection type
ok 212 connection type should match one of the pre-defined types
# teardown
ok 213 error should be null
ok 214 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50148
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 215 peer should have a non-empty identifier
ok 216 host address should be null
ok 217 port number should be null
ok 218 peer should have suggested timeout
ok 219 peer should have a connection type
ok 220 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 221 error should be null
ok 222 error should be null
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# setup
# Can call start/stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 223 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 224 Can call stopListeningForAdvertisements without error
# teardown
ok 225 Should be able to call stopListeningForAdvertisements in teardown
ok 226 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 227 Can call startListeningForAdvertisements without error
ok 228 Can call startListeningForAdvertisements twice without error
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 229 Should be able to call stopListeningForAdvertisements in teardown
ok 230 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 231 Can call stopListeningForAdvertisements without error
ok 232 Can call stopListeningForAdvertisements without error
# teardown
ok 233 Should be able to call stopListeningForAdvertisements in teardown
ok 234 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 235 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 236 Can call stopAdvertisingAndListening without error
# teardown
ok 237 Should be able to call stopListeningForAdvertisements in teardown
ok 238 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 239 Can call startUpdateAdvertisingAndListening without error
ok 240 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 241 Should be able to call stopListeningForAdvertisements in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 242 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 243 Can call startUpdateAdvertisingAndListening without error
ok 244 Can call stopAdvertisingAndListening without error
# teardown
ok 245 Should be able to call stopListeningForAdvertisements in teardown
ok 246 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 247 got right error
# teardown
ok 248 Should be able to call stopListeningForAdvertisements in teardown
ok 249 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 250 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 251 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 252 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 253 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50154
ok 254 no errors
ok 255 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 256 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50156
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 257 no errors
ok 258 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 259 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50158
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 260 no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 261 still no errors
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 262 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50162
ok 263 no errors
ok 264 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 265 must be stopped
# setup
# can get the network status before starting
ok 266 network status should have certain non-empty properties
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 267 must be stopped
# setup
# error returned with bad router
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 268 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 269 must be stopped
# setup
# all services are stopped when we call stop
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50164
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 270 connection to servers manager should succeed after starting
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
ok 271 connection to router server should succeed after starting
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 272 is stopped after calling stop
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 273 connection to servers manager should fail after stopping
ok 274 connection to router server should fail after stopping
# teardown
ok 275 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 276 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 277 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 278 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 279 must be stopped
# setup
# make sure we actually call kill connections properly
ok 280 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 281 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50172
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50171,"error":{}}
ok 282 failure reason is as expected
ok 283 error description is as expected
ok 284 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 285 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50174
ok 286 peerIdentifier matches
ok 287 error description matches
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 288 must be stopped
# setup
# can do HTTP requests between peers without coordinator
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50176
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener creating new server
DEBUG createPeerListener: pleaseConnect= false
ok 289 found a peer! {"peerIdentifier":"foo","portNumber":50179,"hostAddress":"127.0.0.1"}
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
ok 290 Should only get expected id
ok 291 response body should match testData
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 292 must be stopped
DEBUG createNativeListener: incoming socket close
# setup
# make sure bad PSK connections fail
ok 293 FIX ME, PLEASE!!!
# teardown
ok 294 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# setup
# peer changes handled from a queue
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50187
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
ok 295 peers were handled in the right order
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 296 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50199
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 297 discovery is active
ok 298 advertising is active
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 299 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50201
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50201
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 300 right error reason
ok 301 Stop should be fine
ok 302 same port
ok 303 we should be off
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 304 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50205
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 305 discoveryActive matches
ok 306 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 307 discoveryActive matches
ok 308 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50207
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 309 discoveryActive matches
ok 310 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 311 discoveryActive matches
ok 312 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50211
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
ok 313 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 314 peerIdentifier should be identifier
ok 315 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 316 good beacon
ok 317 good preAmble
ok 318 public keys match!
ok 319 must return null after successful call
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 320 Response should be HTTP_BAD_RESPONSE
ok 321 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 322 Response should be NETWORK_PROBLEM
ok 323 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 324 Call start once
ok 325 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 326 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 327 Should be Killed
ok 328 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 329 Should be KILLED
ok 330 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 331 Should be KILLED
ok 332 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 333 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 334 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 335 Should be NETWORK_PROBLEM caused closing server socket
ok 336 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 337 Should be NETWORK_PROBLEM caused closing client socket
ok 338 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 339 publicKeysToNotify cannot be null
ok 340 ecdh for local device cannot be null
ok 341 milliseconds cannot be less than 0
ok 342 milliseconds cannot be 0
ok 343 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 344 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 345 should be equal
ok 346 should be equal
ok 347 should be truthy
ok 348 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 349 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 350 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 351 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 352 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 353 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 354 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 355 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 356 should be equal
ok 357 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 358 should be equal
ok 359 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 360 right number of calls to address book
ok 361 good preAmble
ok 362 good unencryptedKeyId
ok 363 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 364 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 365 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 366 Matching numbers
ok 367 We have an entry!
ok 368 keys match
ok 369 secrets match
ok 370 We have an entry!
ok 371 keys match
ok 372 secrets match
ok 373 We have an entry!
ok 374 keys match
ok 375 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 376 Streams have same length
ok 377 matching size
ok 378 keys match
ok 379 secrets match
# teardown
# setup
# Add two Peers.
ok 380 should be equal
ok 381 should be equal
ok 382 should be equal
ok 383 should be equal
ok 384 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 385 should be equal
ok 386 should be equal
# teardown
# setup
# Resolves an action locally
ok 387 Host address must match
ok 388 suggestedTCPTimeout must match
ok 389 connectionType must match
ok 390 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 391 Host address must match
ok 392 suggestedTCPTimeout must match
ok 393 connectionType must match
ok 394 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 395 should be equal
ok 396 should be equal
ok 397 should be equal
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 398 should be equal
# teardown
# setup
# Client to server request locally
ok 399 secrets are equal
ok 400 Public key matches with the server key
ok 401 Host address must match
ok 402 suggestedTCPTimeout must match
ok 403 connectionType must match
ok 404 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 405 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 406 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 407 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 408 All keys need to be available in the cache
ok 409 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 410 Size of the cache should be 2
ok 411 Cache doesn't contain dictionary1
ok 412 Size of the cache should be 1
ok 413 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 414 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 415 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 416 StartUpdateAdvertisingAndListening should not be called
ok 417 ThaliMobile.StopAdvertisingAndListening should be called once
ok 418 no error
ok 419 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 420 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 421 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 422 no error
ok 423 should be 200
ok 424 should be equal
ok 425 should be equal
ok 426 should be truthy
ok 427 no error
ok 428 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 429 error should be null
ok 430 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 431 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 432 getPeerIdentifier
ok 433 getConnectionType
ok 434 getActionType
ok 435 getActionState
ok 436 getPskIdentity
ok 437 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 438 initial state
ok 439 after start
ok 440 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 441 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 442 clean kill
ok 443 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 444 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 445 connection type works
ok 446 getHostAddress works
ok 447 getPortNumber works
ok 448 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 449 Entry counter must be 1
ok 450 Size must be 1
ok 451 Entry counter must be 2
ok 452 Size must be 2
ok 453 Entry2 should not be found
ok 454 Size must be 1
ok 455 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 456 Size must be100
ok 457 Entries between 20 and MAXSIZE + 20 should exist
ok 458 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 459 Entries between 6 and MAXSIZE + 4 should exist
ok 460 Size should be MAXSIZE
ok 461 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 462 WAITING state entry should not be removed
ok 463 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 464 Size should be MAXSIZE
ok 465 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 466 Kill should be called once
ok 467 Size should be 100
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 468 null arg
ok 469 wrong arg type
ok 470 wrong state
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 471 good enqueue
ok 472 should be equal
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 473 good enqueue
ok 474 2nd good enqueue
ok 475 we are in the pool
ok 476 We are out of the pool
ok 477 Action was killed
ok 478 The original kill was called too
ok 479 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 480 good enqueue
ok 481 first kill
ok 482 second NOOP kill
# teardown
# setup
# compareBufferArrays
ok 483 should throw
ok 484 should throw
ok 485 should be falsy
ok 486 should be falsy
ok 487 should be truthy
ok 488 should be truthy
ok 489 should be truthy
# teardown
# setup
# Call start twice and get error
ok 490 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 491 should be truthy
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 492 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 493 should be equal
ok 494 should be equal
ok 495 should throw
# teardown
# setup
# Test TransientState
ok 496 should throw
ok 497 should throw
ok 498 should be equal
ok 499 should be equal
ok 500 should be equal
ok 501 should be equal
ok 502 should be truthy
ok 503 should be truthy
# teardown
# setup
# No peers and empty database
ok 504 verify failed
ok 505 constructor called once
ok 506 constructor called with right args
ok 507 match start arg
ok 508 start called once
ok 509 stop called once
ok 510 stop after start
# teardown
# setup
# One peer and empty DB
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 511 verify failed
ok 512 constructor called once
ok 513 constructor called with right args
ok 514 match start arg
ok 515 start called once
ok 516 stop called once
ok 517 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 518 verify failed
ok 519 constructor called once
ok 520 constructor called with right args
ok 521 match start arg
ok 522 start called once
ok 523 stop called once
ok 524 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 525 verify failed
ok 526 constructor called once
ok 527 constructor called with right args
ok 528 match start arg
ok 529 start called once
ok 530 stop called once
ok 531 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 532 verify failed
ok 533 constructor called once
ok 534 constructor called with right args
ok 535 match start arg
ok 536 start called once
ok 537 stop called once
ok 538 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 539 verify failed
ok 540 constructor called once
ok 541 constructor called with right args
ok 542 match start arg
ok 543 start called once
ok 544 stop called once
ok 545 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 546 verify failed
ok 547 constructor called once
ok 548 constructor called with right args
ok 549 match start arg
ok 550 start called once
ok 551 stop called once
ok 552 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 553 verify failed
ok 554 constructor called once
ok 555 constructor called with right args
ok 556 last start before stop
ok 557 empty first start
ok 558 full second start
ok 559 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 560 verify failed
ok 561 constructor called once
ok 562 constructor called with right args
ok 563 start before stop
ok 564 We got at least 3 calls to start
ok 565 at least 3
ok 566 default 1
ok 567 1 run
ok 568 default 2
ok 569 2 run
ok 570 default 3
# teardown
# setup
# start and stop and start and stop
ok 571 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 572 back to null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 573 still null
ok 574 verify failed
ok 575 constructor called once
ok 576 constructor called with right args
ok 577 first start before first stop
ok 578 first stop before second start
ok 579 second start before second stop
# teardown
# setup
# two identical starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 580 verify failed
ok 581 constructor called once
ok 582 constructor called with right args
ok 583 should be truthy
# teardown
# setup
# two different starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 584 verify failed
ok 585 constructor called once
ok 586 constructor called with right args
ok 587 should be truthy
ok 588 should be truthy
# teardown
# setup
# two stops and a start and two stops
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 589 verify failed
ok 590 constructor called once
ok 591 constructor called with right args
ok 592 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 593 verify failed
ok 594 constructor called once
ok 595 constructor called with right args
ok 596 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 597 should be equal
ok 598 should be equal
# teardown
# setup
# can create servers manager
ok 599 serversManager must not be null
ok 600 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 601 We need to call start first
# teardown
# setup
# can start/stop servers manager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50255
ok 602 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50256
ok 603 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50258
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 604 we should be connected
DEBUG createNativeListener: incoming socket close
ok 605 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50260
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50261
# teardown
# setup
ok 606 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 607 peer identifier should match
ok 608 host address should match
ok 609 port should match
ok 610 host address should be null
ok 611 port should should be null
# teardown
ok 612 should not be in started state
# setup
ok 613 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
ok 614 USN should have changed from the first one
ok 615 when receiving the second byebye, the first USN should be already set
# teardown
ok 616 should not be in started state
# setup
ok 617 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 618 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 619 should not have emitted with invalid USN
# teardown
ok 620 should not be in started state
# setup
ok 621 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 622 irrelevant messages should be ignored
ok 623 relevant messages should not be ignored
ok 624 messages from this device should be ignored
# teardown
ok 625 should not be in started state
# setup
ok 626 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 627 specific error should be returned
# teardown
ok 628 should not be in started state
# setup
ok 629 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 630 specific error should be returned
# teardown
ok 631 should not be in started state
# setup
ok 632 should be in started state
# #start should fail if called twice in a row
ok 633 specific error should be received
# teardown
ok 634 should not be in started state
# setup
ok 635 should be in started state
# should not be started after stop is called
ok 636 should not be started
ok 637 should not be listening
ok 638 should not target listening
ok 639 should not be advertising
ok 640 should not target advertising
# teardown
ok 641 should not be in started state
# setup
ok 642 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 643 specific error should be received
# teardown
ok 644 should not be in started state
# setup
ok 645 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 646 specific error expected
# teardown
ok 647 should not be in started state
# setup
ok 648 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
ok 649 server should respond with code 200
# teardown
ok 650 should not be in started state
# setup
ok 651 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
ok 652 Connection should be rejected
# teardown
ok 653 should not be in started state
# setup
ok 654 should be in started state
# #stop can be called multiple times in a row
ok 655 should be in stopped state
ok 656 should still be in stopped state
# teardown
ok 657 should not be in started state
# setup
ok 658 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 659 should be in listening state
ok 660 should still be in listening state
# teardown
ok 661 should not be in started state
# setup
ok 662 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 663 should not be in listening state
ok 664 should still not be in listening state
# teardown
ok 665 should not be in started state
# setup
ok 666 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 667 should not be in advertising state
ok 668 should still not be in advertising state
# teardown
ok 669 should not be in started state
# setup
ok 670 should be in started state
# functions are run from a queue in the right order
ok 671 call order must match
# teardown
ok 672 should not be in started state
# setup
ok 673 should be in started state
# does not get peer changes from self
ok 674 USN must have changed again
# teardown
ok 675 should not be in started state
# setup
ok 676 should be in started state
# network changes are ignored while stopping
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 677 should not be called
# teardown
ok 678 should not be in started state
# setup
ok 679 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 680 wifi should be off
ok 681 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 682 discoveryActive should be true
# teardown
ok 683 should not be in started state
# setup
ok 684 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 685 wifi should be off
ok 686 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 687 advertisingActive should be true
# teardown
ok 688 should not be in started state
# setup
ok 689 should be in started state
# when wifi is enabled discovery is activated and peers become available
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 690 wifi should be off
ok 691 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 692 peer identifier should match
ok 693 host address should match
ok 694 port should match
# teardown
ok 695 should not be in started state
# setup
# #ThaliPeerPoolDefault - single action
ok 696 is an agent
ok 697 enqueue is fine
ok 698 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 699 is an agent
ok 700 first enqueue is fine
ok 701 is an agent
ok 702 second enqueue is fine
ok 703 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 704 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 705 is an agent
ok 706 good enqueue
ok 707 Identity should match
ok 708 Got expected response
ok 709 Got psk call back
# teardown

1..709
# tests 709
# pass  709

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
[36mDownloading:[39m [32mhttp://jxcore.azureedge.net/jxcore-cordova/0.1.2/release/io.jxcore.node.jx
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

Starting to download Thali Cordova plugin from: https://codeload.github.com/thaliproject/Thali_CordovaPlugin/zip/npmv2.1.0
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2183Fb020uBX4l5n/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2183Fb020uBX4l5n/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2183Fb020uBX4l5n/TestApp/plugins/org.thaliproject.p2p/scripts
└─┬ fs-extra-promise@0.2.1 
  ├── bluebird@2.10.2 
  └─┬ fs-extra@0.24.0 
    ├── graceful-fs@4.1.4 
    ├── jsonfile@2.3.1 
    ├── path-is-absolute@1.0.0 
    └─┬ rimraf@2.5.4 
      └─┬ glob@7.0.5 
        ├── fs.realpath@1.0.0 
        ├─┬ inflight@1.0.5 
        │ └── wrappy@1.0.2 
        ├── inherits@2.0.1 
        ├─┬ minimatch@3.0.2 
        │ └─┬ brace-expansion@1.1.6 
        │   ├── balanced-match@0.4.2 
        │   └── concat-map@0.0.1 
        └── once@1.3.3 


npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
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
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2183Fb020uBX4l5n
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

2016-07-25T14:20:10.131Z - info: Require 3 ios devices

2016-07-25T14:20:10.132Z - info: Require 0 android devices
2016-07-25T14:20:10.137Z - info: listening on *:3000

[36m
[39m
[36m/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:711
[39m
[36m      throw new Error('The supplied mobileName does not have a matching ' +
            ^
[39m
[36mError: The supplied mobileName does not have a matching callNative method: ExecuteNativeTests
    at MobileCallInstance.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:711:13)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:18:30)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Function.Module.runMain (module.js:878:12)
    at startup (node.js:485:18)
    at node.js:1604:3
[39m
[32m
[39m
[32m/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:711
[39m
[32m      throw new Error('The supplied mobileName does not have a matching ' +
[39m
[36mundefined[39m
[32m            ^
[39m
[32mError: The supplied mobileName does not have a matching callNative method: ExecuteNativeTests
    at MobileCallInstance.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:711:13)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:18:30)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Function.Module.runMain (module.js:878:12)
    at startup (node.js:485:18)
    at node.js:1604:3
[39m
[32mundefined[39m
[33m
[39m
[33m/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:711
      throw new Error('The supplied mobileName does not have a matching ' +
            ^
[39m
[33mError: The supplied mobileName does not have a matching callNative method: ExecuteNativeTests
    at MobileCallInstance.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/wifiBasedNativeMock.js:711:13)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/UnitTest_app.js:18:30)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Function.Module.runMain (module.js:878:12)
    at startup (node.js:485:18)
    at node.js:1604:3
[39m
[33mundefined[39m

npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch GET https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/encodeurl
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/encodeurl
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/escape-html
npm http 200 https://registry.npmjs.org/depd
npm http fetch GET https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/debug
npm http fetch GET https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/finalhandler
npm http fetch GET https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http 304 https://registry.npmjs.org/fresh
npm http fetch GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/serve-static
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http 304 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/send
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch GET https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http 200 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/range-parser
npm http fetch GET https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http fetch 200 https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http 200 https://registry.npmjs.org/content-type
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/proxy-addr
npm http fetch GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http 200 https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/negotiator
npm http fetch GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http fetch GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http fetch 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http fetch GET https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http fetch 200 https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/statuses
npm http fetch GET https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http fetch GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http 304 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/mime
npm http 200 https://registry.npmjs.org/http-errors
npm http fetch GET https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/setprototypeof
npm http fetch GET https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http 200 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/fs.realpath
npm http fetch GET https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http 200 https://registry.npmjs.org/inflight
npm http 200 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http 304 https://registry.npmjs.org/once
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
npm http 200 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/esprima
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http 200 https://registry.npmjs.org/object-assign
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http 200 https://registry.npmjs.org/base62
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/mkdirp
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
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http fetch GET https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http 200 https://registry.npmjs.org/ast-types
npm http fetch 200 https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/object-keys
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http fetch GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 200 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/base64id
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http 200 https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/utf8
npm http request GET https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/utf8
npm http 200 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/body-parser
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http fetch GET https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http 200 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http fetch 200 https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http 503 https://registry.npmjs.org/ip
npm ERR! registry error parsing json
npm http 503 https://registry.npmjs.org/javascript-state-machine
npm ERR! registry error parsing json
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http 304 https://registry.npmjs.org/multiplex
npm http 200 https://registry.npmjs.org/ip
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/bytes
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/setprototypeof
npm http 200 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
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
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/qs
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/http-errors
npm http fetch GET https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/path-is-absolute
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
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
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
npm http fetch GET https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http 304 https://registry.npmjs.org/end-of-stream
npm http fetch 200 https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http 200 https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/extend
npm http fetch GET https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http 200 https://registry.npmjs.org/har-validator
npm http fetch GET https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/oauth-sign
npm http fetch 200 https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/tough-cookie
npm http 200 https://registry.npmjs.org/hawk
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm WARN engine tough-cookie@2.3.0: wanted: {"node":">=4.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http fetch GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.0.tgz
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/strip-ansi
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/jsprim
npm http 200 https://registry.npmjs.org/sshpk
npm http fetch GET https://registry.npmjs.org/jsprim/-/jsprim-1.3.0.tgz
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
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 200 https://registry.npmjs.org/getpass
npm http 200 https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/dashdash
npm http fetch GET https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch GET https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch 200 https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/espree
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/catharsis
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/wrench
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/marked
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http 304 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/catharsis
npm http 200 https://registry.npmjs.org/espree
npm http 200 https://registry.npmjs.org/bluebird
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/tweetnacl
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/jxc
npm http fetch GET https://registry.npmjs.org/jxc/-/jxc-1.0.15.tgz
npm http 200 https://registry.npmjs.org/unzip
npm http fetch 200 https://registry.npmjs.org/jxc/-/jxc-1.0.15.tgz
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
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
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm WARN engine tough-cookie@2.3.0: wanted: {"node":">=4.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/fstream
npm http 200 https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/chainsaw
npm http 200 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/slice-stream
npm http request GET https://registry.npmjs.org/over
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/proxyquire
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http 200 https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/pouchdb
npm http 200 https://registry.npmjs.org/request-promise
npm http 200 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch GET https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http fetch GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http fetch GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http 200 https://registry.npmjs.org/supertest
npm http fetch GET https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http 200 https://registry.npmjs.org/tmp
npm http 200 https://registry.npmjs.org/sinon
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http 200 https://registry.npmjs.org/uuid
npm http fetch 200 https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http fetch GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http fetch 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http fetch GET https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http fetch GET https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http 200 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http fetch 200 https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http 200 https://registry.npmjs.org/tape-catch
npm http fetch GET https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.6.tgz
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
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/setprototypeof
npm http 304 https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
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
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 200 https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/cookie-parser
npm http fetch GET https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http 200 https://registry.npmjs.org/multiparty
npm http 200 https://registry.npmjs.org/compression
npm http 200 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http fetch GET https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http fetch GET https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http fetch GET https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http fetch GET https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http fetch 200 https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http fetch 200 https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/compressible
npm http fetch GET https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch 200 https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 200 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/argsarray
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.3.tgz
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
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
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 200 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/meow
npm http request GET https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http 200 https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 200 https://registry.npmjs.org/aproba
npm http fetch GET https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http request GET https://registry.npmjs.org/es6-promise-pool
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 200 https://registry.npmjs.org/es6-promise-pool
npm http fetch GET https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 200 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fruitdown
npm http 200 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/scope-eval
npm http fetch GET https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 200 https://registry.npmjs.org/sublevel-pouchdb
npm http fetch GET https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http fetch GET https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http fetch 200 https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 200 https://registry.npmjs.org/vuvuzela
npm http fetch GET https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http fetch 200 https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http fetch 200 https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 304 https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/level-errors
npm http 200 https://registry.npmjs.org/semver
npm http fetch GET https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http fetch 200 https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 200 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/ltgt
npm http 200 https://registry.npmjs.org/functional-red-black-tree
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
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/tunnel-agent
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/delayed-stream
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
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/pull-stream
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
npm http 200 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/is-array
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http 200 https://registry.npmjs.org/is-array
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http fetch GET https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 200 https://registry.npmjs.org/equals
npm http fetch GET https://registry.npmjs.org/equals/-/equals-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/equals/-/equals-1.0.5.tgz
npm http request GET https://registry.npmjs.org/jkroso-type
npm http 304 https://registry.npmjs.org/jkroso-type
npm http request GET https://registry.npmjs.org/pouchdb-route
npm http 304 https://registry.npmjs.org/pouchdb-route
npm http request GET https://registry.npmjs.org/get-folder-size
npm http 304 https://registry.npmjs.org/get-folder-size
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/fast-future
npm http 200 https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 200 https://registry.npmjs.org/stream-shift
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/propagate
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http 200 https://registry.npmjs.org/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http request GET https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http fetch GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http 200 https://registry.npmjs.org/resolve
npm http request GET https://registry.npmjs.org/is-object
npm http 200 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm WARN engine tough-cookie@2.3.0: wanted: {"node":">=4.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 200 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parsejson
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/yeast
npm http 200 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/blob
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
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
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/reduce-component
npm http 200 https://registry.npmjs.org/cookiejar
npm http 200 https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/has
npm http 200 https://registry.npmjs.org/object-inspect
npm http 200 https://registry.npmjs.org/function-bind
npm http fetch GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http fetch 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http request GET https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/define-properties
npm http 200 https://registry.npmjs.org/es-abstract
npm http fetch GET https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http fetch 200 https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http request GET https://registry.npmjs.org/is-callable
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http 304 https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/global
npm http 200 https://registry.npmjs.org/global
npm http fetch GET https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http request GET https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/min-document
npm http 200 https://registry.npmjs.org/process
npm http fetch GET https://registry.npmjs.org/process/-/process-0.5.2.tgz
npm http fetch GET https://registry.npmjs.org/min-document/-/min-document-2.18.0.tgz
npm http fetch 200 https://registry.npmjs.org/process/-/process-0.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/min-document/-/min-document-2.18.0.tgz
npm http request GET https://registry.npmjs.org/dom-walk
npm http 200 https://registry.npmjs.org/dom-walk
npm http fetch GET https://registry.npmjs.org/dom-walk/-/dom-walk-0.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/dom-walk/-/dom-walk-0.1.1.tgz
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
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

Error: Command failed: npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch GET https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/encodeurl
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/encodeurl
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/escape-html
npm http 200 https://registry.npmjs.org/depd
npm http fetch GET https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/debug
npm http fetch GET https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/finalhandler
npm http fetch GET https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http 304 https://registry.npmjs.org/fresh
npm http fetch GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http 200 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/serve-static
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http 304 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/send
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch GET https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http 200 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/range-parser
npm http fetch GET https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch 200 https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http fetch 200 https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http 200 https://registry.npmjs.org/content-type
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/proxy-addr
npm http fetch GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http 200 https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/negotiator
npm http fetch GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http fetch GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http fetch 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http fetch GET https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http fetch 200 https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/statuses
npm http fetch GET https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http fetch GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http 304 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/mime
npm http 200 https://registry.npmjs.org/http-errors
npm http fetch GET https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/setprototypeof
npm http fetch GET https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http 200 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/fs.realpath
npm http fetch GET https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http 200 https://registry.npmjs.org/inflight
npm http 200 https://registry.npmjs.org/minimatch
npm http fetch GET https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/inflight/-/inflight-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.2.tgz
npm http 304 https://registry.npmjs.org/once
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
npm http 200 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/esprima
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http 200 https://registry.npmjs.org/object-assign
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http 200 https://registry.npmjs.org/base62
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/mkdirp
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
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http fetch GET https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http 200 https://registry.npmjs.org/ast-types
npm http fetch 200 https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/object-keys
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.34.tgz
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http fetch GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.1.tgz
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 200 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/base64id
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http 200 https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/utf8
npm http request GET https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/utf8
npm http 200 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/defined
npm http 200 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/body-parser
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http fetch GET https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http 200 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http fetch 200 https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http 503 https://registry.npmjs.org/ip
npm ERR! registry error parsing json
npm http 503 https://registry.npmjs.org/javascript-state-machine
npm ERR! registry error parsing json
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http 304 https://registry.npmjs.org/multiplex
npm http 200 https://registry.npmjs.org/ip
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/bytes
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/setprototypeof
npm http 200 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
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
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/qs
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.3.tgz
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/http-errors
npm http fetch GET https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/path-is-absolute
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
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
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
npm http fetch GET https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http 304 https://registry.npmjs.org/end-of-stream
npm http fetch 200 https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http 200 https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/caseless
npm http 200 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/extend
npm http fetch GET https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http 200 https://registry.npmjs.org/har-validator
npm http fetch GET https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/oauth-sign
npm http fetch 200 https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/tough-cookie
npm http 200 https://registry.npmjs.org/hawk
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm WARN engine tough-cookie@2.3.0: wanted: {"node":">=4.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http fetch GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.0.tgz
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/strip-ansi
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/jsprim
npm http 200 https://registry.npmjs.org/sshpk
npm http fetch GET https://registry.npmjs.org/jsprim/-/jsprim-1.3.0.tgz
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
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 200 https://registry.npmjs.org/getpass
npm http 200 https://registry.npmjs.org/asn1
npm http 200 https://registry.npmjs.org/dashdash
npm http fetch GET https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch GET https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/getpass/-/getpass-0.1.6.tgz
npm http fetch 200 https://registry.npmjs.org/dashdash/-/dashdash-1.14.0.tgz
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/espree
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/catharsis
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/wrench
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/marked
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http 304 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/catharsis
npm http 200 https://registry.npmjs.org/espree
npm http 200 https://registry.npmjs.org/bluebird
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/tweetnacl
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/jxc
npm http fetch GET https://registry.npmjs.org/jxc/-/jxc-1.0.15.tgz
npm http 200 https://registry.npmjs.org/unzip
npm http fetch 200 https://registry.npmjs.org/jxc/-/jxc-1.0.15.tgz
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
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
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm WARN engine tough-cookie@2.3.0: wanted: {"node":">=4.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/fstream
npm http 200 https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/chainsaw
npm http 200 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/slice-stream
npm http request GET https://registry.npmjs.org/over
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/proxyquire
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http 200 https://registry.npmjs.org/socket.io-client
npm http 200 https://registry.npmjs.org/pouchdb
npm http 200 https://registry.npmjs.org/request-promise
npm http 200 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch GET https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http fetch GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http fetch GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http 200 https://registry.npmjs.org/supertest
npm http fetch GET https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http 200 https://registry.npmjs.org/tmp
npm http 200 https://registry.npmjs.org/sinon
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http 200 https://registry.npmjs.org/uuid
npm http fetch 200 https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http fetch GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http fetch 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http fetch GET https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http fetch GET https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http 200 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http fetch 200 https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http 200 https://registry.npmjs.org/tape-catch
npm http fetch GET https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.6.tgz
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
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/setprototypeof
npm http 304 https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
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
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 200 https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/cookie-parser
npm http fetch GET https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http 200 https://registry.npmjs.org/multiparty
npm http 200 https://registry.npmjs.org/compression
npm http 200 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http fetch GET https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http fetch GET https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http fetch GET https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http fetch GET https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http fetch 200 https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http fetch 200 https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/compressible
npm http fetch GET https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch 200 https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 200 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/argsarray
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.3.tgz
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
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
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 200 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/meow
npm http request GET https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http 200 https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 200 https://registry.npmjs.org/aproba
npm http fetch GET https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http request GET https://registry.npmjs.org/es6-promise-pool
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 200 https://registry.npmjs.org/es6-promise-pool
npm http fetch GET https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 200 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fruitdown
npm http 200 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/scope-eval
npm http fetch GET https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 200 https://registry.npmjs.org/sublevel-pouchdb
npm http fetch GET https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http fetch GET https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http fetch 200 https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 200 https://registry.npmjs.org/vuvuzela
npm http fetch GET https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http fetch 200 https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http fetch 200 https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 304 https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/level-errors
npm http 200 https://registry.npmjs.org/semver
npm http fetch GET https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http fetch 200 https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 200 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/ltgt
npm http 200 https://registry.npmjs.org/functional-red-black-tree
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
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/tunnel-agent
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/delayed-stream
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
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 200 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/pull-stream
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
npm http 200 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/is-array
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http 200 https://registry.npmjs.org/is-array
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http fetch GET https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 200 https://registry.npmjs.org/equals
npm http fetch GET https://registry.npmjs.org/equals/-/equals-1.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/equals/-/equals-1.0.5.tgz
npm http request GET https://registry.npmjs.org/jkroso-type
npm http 304 https://registry.npmjs.org/jkroso-type
npm http request GET https://registry.npmjs.org/pouchdb-route
npm http 304 https://registry.npmjs.org/pouchdb-route
npm http request GET https://registry.npmjs.org/get-folder-size
npm http 304 https://registry.npmjs.org/get-folder-size
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/fast-future
npm http 200 https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 200 https://registry.npmjs.org/stream-shift
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/propagate
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http 200 https://registry.npmjs.org/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http request GET https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http fetch GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http 200 https://registry.npmjs.org/resolve
npm http request GET https://registry.npmjs.org/is-object
npm http 200 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm WARN engine tough-cookie@2.3.0: wanted: {"node":">=4.0"} (current: {"node":"0.10.40","npm":"3.3.12"})
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 200 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parsejson
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/yeast
npm http 200 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/blob
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
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
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/reduce-component
npm http 200 https://registry.npmjs.org/cookiejar
npm http 200 https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/has
npm http 200 https://registry.npmjs.org/object-inspect
npm http 200 https://registry.npmjs.org/function-bind
npm http fetch GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http fetch 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http request GET https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/define-properties
npm http 200 https://registry.npmjs.org/es-abstract
npm http fetch GET https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http fetch 200 https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http request GET https://registry.npmjs.org/is-callable
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http 304 https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/global
npm http 200 https://registry.npmjs.org/global
npm http fetch GET https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http request GET https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/min-document
npm http 200 https://registry.npmjs.org/process
npm http fetch GET https://registry.npmjs.org/process/-/process-0.5.2.tgz
npm http fetch GET https://registry.npmjs.org/min-document/-/min-document-2.18.0.tgz
npm http fetch 200 https://registry.npmjs.org/process/-/process-0.5.2.tgz
npm http fetch 200 https://registry.npmjs.org/min-document/-/min-document-2.18.0.tgz
npm http request GET https://registry.npmjs.org/dom-walk
npm http 200 https://registry.npmjs.org/dom-walk
npm http fetch GET https://registry.npmjs.org/dom-walk/-/dom-walk-0.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/dom-walk/-/dom-walk-0.1.1.tgz
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
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
