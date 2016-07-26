#### Test (Fail) 77622416 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
 * [new branch]      malloc_error -> origin/malloc_error
   f44671b..adf9d02  vNext_aaladev_507 -> origin/vNext_aaladev_507
   460b864..8305465  vNext_ilya_771 -> origin/vNext_ilya_771
   5805f9f..75fe645  vNext_jareksl_555_clean -> origin/vNext_jareksl_555_clean

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '75fe645'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 75fe645... Merge pull request #792 from jareksl/vNext_jareksl_555_clean

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
│ ├── tough-cookie@2.3.1 
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
│ ├── tough-cookie@2.3.1 
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
│ │ ├── tough-cookie@2.3.1 
│ │ └── tunnel-agent@0.4.3 
│ └── urlsafe-base64@1.0.0 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.1 
├── urlsafe-base64@1.0.0 
└── uuid@2.0.2 

thali-test-server@0.0.1 /Users/thali/Github/testBuild/test/TestServer
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

Creating a new cordova project.
Adding ios project...
iOS project created with cordova-ios@4.1.1
Discovered plugin "cordova-plugin-whitelist" in config.xml. Installing to the project
Fetching plugin "cordova-plugin-whitelist@1" via npm
Installing "cordova-plugin-whitelist" for ios
Adding android project...
Creating Cordova project for the Android platform:
	Path: platforms/android
	Package: com.test.thalitest
	Name: ThaliTest
	Activity: MainActivity
	Android target: android-23
Android project created with cordova-android@5.1.1
Installing "cordova-plugin-whitelist" for android

               This plugin is only applicable for versions of cordova-android greater than 4.0. If you have a previous platform version, you do *not* need this plugin since the whitelist will be built in.
          

> thali@2.1.0 prepublish /Users/thali/Github/testBuild/thali
> jx install/prePublishThaliCordovaPlugin.js


> thali@2.1.0 postinstall /Users/thali/Github/ThaliTest/www/jxcore/node_modules/thali
> jx installCordovaPlugin.js

install@0.0.1 /Users/thali/Github/ThaliTest/www/jxcore/node_modules/thali/install
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


npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/jxc
npm http 304 https://registry.npmjs.org/unzip
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/minimatch
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
npm http 304 https://registry.npmjs.org/adm-zip
npm http 304 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/immediate
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
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/mkdirp
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
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
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
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
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
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/is-my-json-valid
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
npm http 200 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/setimmediate
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/match-stream
npm http 200 https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/traverse
npm http 304 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 200 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.

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

Copying files from /Users/thali/Github/Thali_CordovaPlugin to /Users/thali/Github/ThaliTest/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Adding Thali Cordova plugin from: /Users/thali/Github/ThaliTest/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Installing "org.thaliproject.p2p" for android
android-sdk version check failed ("/Users/thali/Github/ThaliTest/platforms/android/cordova/android_sdk_version"), continuing anyways.
Installing "org.thaliproject.p2p" for ios

Running jx npm install in: /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/scripts
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
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
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
npm WARN EPACKAGEJSON scripts@0.0.1 No repository field.

thali-cordova-plugin-jxcore@1.0.0 /Users/thali/Github/ThaliTest/www/jxcore
└─┬ thali@2.1.0 
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
  │ │   └─┬ getpass@0.1.6 
  │ │     └── assert-plus@1.0.0 
  │ ├── is-typedarray@1.0.0 
  │ ├── isstream@0.1.2 
  │ ├── json-stringify-safe@5.0.1 
  │ ├─┬ mime-types@2.1.11 
  │ │ └── mime-db@1.23.0 
  │ ├── oauth-sign@0.8.2 
  │ ├── stringstream@0.0.5 
  │ ├── tough-cookie@2.3.1 
  │ └── tunnel-agent@0.4.3 
  ├── urlsafe-base64@1.0.0 
  └─┬ winston@2.2.0 
    ├── async@1.0.0 
    ├── colors@1.0.3 
    ├── cycle@1.0.3 
    ├── eyes@0.1.8 
    ├── pkginfo@0.3.1 
    └── stack-trace@0.0.9 


> leveldown-mobile@1.1.1 install /Users/thali/Github/ThaliTest/www/jxcore/node_modules/leveldown-mobile
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
thali-cordova-plugin-jxcore@1.0.0 /Users/thali/Github/ThaliTest/www/jxcore
├── balanced-match@0.2.1 
├── bn.js@4.11.5 
├── body-parser@1.15.2 
├── concat-map@0.0.1 
├─┬ express@4.13.3 
│ ├── depd@1.0.1 
│ ├── qs@4.0.0 
│ └─┬ send@0.13.0
│   └── depd@1.0.1 
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
│ │ │ ├── extend@1.3.0 
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
│ │ │   └── unreachable-branch-transform@0.3.0 
│ │ ├── pouchdb-upsert@2.0.2 
│ │ └── spark-md5@0.0.5 
│ ├─┬ pouchdb-list@1.1.0 
│ │ ├─┬ couchdb-objects@1.0.7 
│ │ │ ├── extend@1.3.0 
│ │ │ ├── is-empty@0.0.1 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├─┬ couchdb-render@1.0.1 
│ │ │ └── extend@1.3.0 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-replicator@2.1.3 
│ │ ├─┬ equals@1.0.5 
│ │ │ └── jkroso-type@1.1.1 
│ │ ├── extend@1.3.0 
│ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ ├── bluebird@1.2.4 
│ │ │ └── lie@2.7.7 
│ │ └── random-uuid-v4@0.0.4 
│ ├─┬ pouchdb-rewrite@1.0.7 
│ │ ├── extend@1.3.0 
│ │ └─┬ pouchdb-route@1.0.3 
│ │   └── extend@1.3.0 
│ ├─┬ pouchdb-security@1.2.6 
│ │ ├── extend@1.3.0 
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
│ │ ├─┬ couchdb-eval@1.0.6 
│ │ │ └── extend@1.3.0 
│ │ ├─┬ couchdb-resp-completer@1.0.3 
│ │ │ └── extend@1.3.0 
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
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.4 
│     └── glob@7.0.5 
├── is-property@1.0.2 
├─┬ leveldown-mobile@1.1.1 
│ ├── abstract-leveldown@2.1.4 
│ ├── bindings@1.2.1 
│ └── fast-future@1.0.1 
├─┬ lie@3.0.4 
│ └── unreachable-branch-transform@0.3.0 
├── long@3.2.0 
├── minimist@1.2.0 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.5
│ │ └─┬ readable-stream@2.1.4 
│ │   └── isarray@1.0.0 
│ └─┬ readable-stream@2.1.4 
│   └── isarray@1.0.0 
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
│ └── propagate@0.3.1 
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
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
│ ├─┬ bl@1.1.2
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ └─┬ har-validator@2.0.6
│   └─┬ is-my-json-valid@2.13.1
│     └─┬ generate-object-property@1.2.0
│       └── is-property@1.0.2 
├─┬ request-promise@0.4.3 
│ ├── bluebird@2.10.2 
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
├─┬ supertest@1.2.0 
│ └─┬ superagent@1.8.3 
│   ├── cookiejar@2.0.6 
│   ├── form-data@1.0.0-rc3 
│   ├── formidable@1.0.17 
│   ├── qs@2.3.3 
│   ├── readable-stream@1.0.27-1 
│   └── reduce-component@1.0.1 
├─┬ supertest-as-promised@2.0.2 
│ └── bluebird@2.10.2 
├─┬ tape@4.6.0 
│ ├── function-bind@1.1.0 
│ ├─┬ glob@7.0.5 
│ │ ├── fs.realpath@1.0.0 
│ │ └─┬ minimatch@3.0.2
│ │   └─┬ brace-expansion@1.1.6
│ │     └── concat-map@0.0.1 
│ ├── has@1.0.1 
│ ├── object-inspect@1.2.1 
│ ├── resumer@0.0.0 
│ └─┬ string.prototype.trim@1.1.2 
│   ├── define-properties@1.1.2 
│   └─┬ es-abstract@1.5.1 
│     ├─┬ es-to-primitive@1.1.1 
│     │ ├── is-date-object@1.0.1 
│     │ └── is-symbol@1.0.1 
│     ├── is-callable@1.1.3 
│     └── is-regex@1.0.3 
├─┬ tape-catch@1.0.6 
│ └─┬ global@4.3.0 
│   ├─┬ min-document@2.18.0 
│   │ └── dom-walk@0.1.1 
│   └── process@0.5.2 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.1 
├── urlsafe-base64@1.0.0 
└── uuid@2.0.2 

UnitTest_app.js -> app.js
UT files will be copied to the platform directory
Preparing UT test environment
Removing UT flag
ANDROID_HOME=/Users/thali/Library/Android/sdk
JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.7.0_79.jdk/Contents/Home
Download https://bintray.com/artifact/download/thali/Thali/org/thaliproject/p2p/btconnectorlib/btconnectorlib2/0.3.2/btconnectorlib2-0.3.2.pom
Download https://repo1.maven.org/maven2/junit/junit/4.12/junit-4.12.pom
Download https://repo1.maven.org/maven2/org/mockito/mockito-core/1.10.19/mockito-core-1.10.19.pom
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker/1.4/dexmaker-1.4.pom
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker-parent/1.4/dexmaker-parent-1.4.pom
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker-dx/1.4/dexmaker-dx-1.4.pom
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker-mockito/1.4/dexmaker-mockito-1.4.pom
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom
Download https://repo1.maven.org/maven2/com/squareup/javawriter/2.1.1/javawriter-2.1.1.pom
Download https://repo1.maven.org/maven2/javax/inject/javax.inject/1/javax.inject-1.pom
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.pom
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-integration/1.3/hamcrest-integration-1.3.pom
Download https://repo1.maven.org/maven2/com/google/code/findbugs/jsr305/2.0.1/jsr305-2.0.1.pom
Download https://repo1.maven.org/maven2/javax/annotation/javax.annotation-api/1.2/javax.annotation-api-1.2.pom
Download https://repo1.maven.org/maven2/net/java/jvnet-parent/3/jvnet-parent-3.pom
Download https://repo1.maven.org/maven2/org/objenesis/objenesis/2.1/objenesis-2.1.pom
Download https://repo1.maven.org/maven2/org/objenesis/objenesis-parent/2.1/objenesis-parent-2.1.pom
Download https://bintray.com/artifact/download/thali/Thali/org/thaliproject/p2p/btconnectorlib/btconnectorlib2/0.3.2/btconnectorlib2-0.3.2.aar
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar
Download https://repo1.maven.org/maven2/junit/junit/4.12/junit-4.12.jar
Download https://repo1.maven.org/maven2/com/squareup/javawriter/2.1.1/javawriter-2.1.1.jar
Download https://repo1.maven.org/maven2/javax/inject/javax.inject/1/javax.inject-1.jar
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-library/1.3/hamcrest-library-1.3.jar
Download https://repo1.maven.org/maven2/org/hamcrest/hamcrest-integration/1.3/hamcrest-integration-1.3.jar
Download https://repo1.maven.org/maven2/com/google/code/findbugs/jsr305/2.0.1/jsr305-2.0.1.jar
Download https://repo1.maven.org/maven2/javax/annotation/javax.annotation-api/1.2/javax.annotation-api-1.2.jar
Download https://repo1.maven.org/maven2/org/objenesis/objenesis/2.1/objenesis-2.1.jar
Download https://repo1.maven.org/maven2/org/mockito/mockito-core/1.10.19/mockito-core-1.10.19.jar
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker/1.4/dexmaker-1.4.jar
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker-dx/1.4/dexmaker-dx-1.4.jar
Download https://repo1.maven.org/maven2/com/crittercism/dexmaker/dexmaker-mockito/1.4/dexmaker-mockito-1.4.jar
:preBuild UP-TO-DATE
:preReleaseBuild UP-TO-DATE
:checkReleaseManifest
:CordovaLib:preBuild UP-TO-DATE
:CordovaLib:preReleaseBuild UP-TO-DATE
:CordovaLib:compileReleaseNdk UP-TO-DATE
:CordovaLib:compileLint
:CordovaLib:copyReleaseLint UP-TO-DATE
:CordovaLib:mergeReleaseProguardFiles
:CordovaLib:packageReleaseRenderscript UP-TO-DATE
:CordovaLib:checkReleaseManifest
:CordovaLib:prepareReleaseDependencies
:CordovaLib:compileReleaseRenderscript
:CordovaLib:generateReleaseResValues
:CordovaLib:generateReleaseResources
:CordovaLib:packageReleaseResources
:CordovaLib:compileReleaseAidl
:CordovaLib:generateReleaseBuildConfig
:CordovaLib:generateReleaseAssets UP-TO-DATE
:CordovaLib:mergeReleaseAssets
:CordovaLib:processReleaseManifest
:CordovaLib:processReleaseResources
:CordovaLib:generateReleaseSources
:CordovaLib:compileReleaseJavaWithJavac
:CordovaLib:processReleaseJavaRes UP-TO-DATE
:CordovaLib:transformResourcesWithMergeJavaResForRelease
:CordovaLib:transformClassesAndResourcesWithSyncLibJarsForRelease
:CordovaLib:mergeReleaseJniLibFolders
:CordovaLib:transformNative_libsWithMergeJniLibsForRelease
:CordovaLib:transformNative_libsWithSyncJniLibsForRelease
:CordovaLib:bundleRelease
:prepareAndroidCordovaLibUnspecifiedReleaseLibrary
:preDebugBuild UP-TO-DATE
:CordovaLib:preDebugBuild UP-TO-DATE
:CordovaLib:compileDebugNdk UP-TO-DATE
:CordovaLib:copyDebugLint UP-TO-DATE
:CordovaLib:mergeDebugProguardFiles
:CordovaLib:packageDebugRenderscript UP-TO-DATE
:CordovaLib:checkDebugManifest
:CordovaLib:prepareDebugDependencies
:CordovaLib:compileDebugRenderscript
:CordovaLib:generateDebugResValues
:CordovaLib:generateDebugResources
:CordovaLib:packageDebugResources
:CordovaLib:compileDebugAidl
:CordovaLib:generateDebugBuildConfig
:CordovaLib:generateDebugAssets UP-TO-DATE
:CordovaLib:mergeDebugAssets
:CordovaLib:processDebugManifest
:CordovaLib:processDebugResources
:CordovaLib:generateDebugSources
:CordovaLib:compileDebugJavaWithJavac
:CordovaLib:processDebugJavaRes UP-TO-DATE
:CordovaLib:transformResourcesWithMergeJavaResForDebug
:CordovaLib:transformClassesAndResourcesWithSyncLibJarsForDebug
:CordovaLib:mergeDebugJniLibFolders
:CordovaLib:transformNative_libsWithMergeJniLibsForDebug
:CordovaLib:transformNative_libsWithSyncJniLibsForDebug
:CordovaLib:bundleDebug
:prepareComAndroidSupportAppcompatV72220Library
:prepareComAndroidSupportSupportV42220Library
:prepareComAndroidSupportTestEspressoEspressoCore22Library
:prepareComAndroidSupportTestEspressoEspressoIdlingResource22Library
:prepareComAndroidSupportTestExposedInstrumentationApiPublish03Library
:prepareComAndroidSupportTestRules03Library
:prepareComAndroidSupportTestRunner03Library
:prepareOrgThaliprojectP2pBtconnectorlibBtconnectorlib2032Library
:prepareReleaseDependencies
:compileReleaseAidl
:compileReleaseRenderscript
:generateReleaseBuildConfig
:generateReleaseAssets UP-TO-DATE
:mergeReleaseAssets
:generateReleaseResValues
:generateReleaseResources
:mergeReleaseResources
:processReleaseManifest
:processReleaseResources
:generateReleaseSources
:compileReleaseJavaWithJavac
:compileReleaseNdk UP-TO-DATE
:compileReleaseSources
:lintVitalRelease
:transformClassesWithDexForRelease
:mergeReleaseJniLibFolders
:transformNative_libsWithMergeJniLibsForRelease
:processReleaseJavaRes UP-TO-DATE
:transformResourcesWithMergeJavaResForRelease
:packageRelease
:assembleRelease
:cdvBuildRelease

BUILD SUCCESSFUL

Total time: 3 mins 9.812 secs
Built the following apk(s): 
	/Users/thali/Github/ThaliTest/platforms/android/build/outputs/apk/android-release-unsigned.apk
Building project  : /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest.xcodeproj
	Configuration : Debug
	Platform      : device
Build settings from command line:
    ARCHS = armv7 arm64
    CONFIGURATION_BUILD_DIR = /Users/thali/Github/ThaliTest/platforms/ios/build/device
    SDKROOT = iphoneos9.2
    SHARED_PRECOMPS_DIR = /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch
    VALID_ARCHS = armv7 arm64

Build settings from configuration file '/Users/thali/Github/ThaliTest/platforms/ios/cordova/build-debug.xcconfig':
    CLANG_ALLOW_NON_MODULAR_INCLUDES_IN_FRAMEWORK_MODULES = YES
    CODE_SIGN_IDENTITY = iPhone Developer
    ENABLE_BITCODE = NO
    GCC_PREPROCESSOR_DEFINITIONS = DEBUG=1
    HEADER_SEARCH_PATHS = "$(TARGET_BUILD_DIR)/usr/local/lib/include" "$(OBJROOT)/UninstalledProducts/include" "$(OBJROOT)/UninstalledProducts/$(PLATFORM_NAME)/include" "$(BUILT_PRODUCTS_DIR)"
    IPHONEOS_DEPLOYMENT_TARGET = 8.0
    OTHER_LDFLAGS = -ObjC
    SWIFT_OBJC_BRIDGING_HEADER = $(PROJECT_DIR)/$(PROJECT_NAME)/Bridging-Header.h
    TARGETED_DEVICE_FAMILY = 1,2

=== BUILD TARGET CordovaLib OF PROJECT CordovaLib WITH CONFIGURATION Debug ===

Check dependencies

Write auxiliary files
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/Cordova.LinkFileList
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova.hmap
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-non-framework-target-headers.hmap
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch.pch.hash-criteria
write-file /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap

CpHeader Classes/Public/CDVScreenOrientationDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVScreenOrientationDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVScreenOrientationDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDV.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDV.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDV.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVWebViewEngineProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVWebViewEngineProtocol.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWebViewEngineProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVCommandDelegateImpl.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVCommandDelegateImpl.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegateImpl.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVCommandQueue.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVCommandQueue.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandQueue.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVWhitelist.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVWhitelist.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVAppDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVAppDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVPlugin+Resources.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVPlugin+Resources.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin+Resources.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVAvailability.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVAvailability.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAvailability.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVUIWebViewDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVPluginResult.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVPluginResult.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPluginResult.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/NSMutableArray+QueueAdditions.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/NSMutableArray+QueueAdditions.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSMutableArray+QueueAdditions.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVInvokedUrlCommand.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVInvokedUrlCommand.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVInvokedUrlCommand.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/NSDictionary+CordovaPreferences.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/NSDictionary+CordovaPreferences.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSDictionary+CordovaPreferences.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVPlugin.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVPlugin.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVURLProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVURLProtocol.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVCommandDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVCommandDelegate.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegate.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVAvailabilityDeprecated.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVAvailabilityDeprecated.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAvailabilityDeprecated.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVUserAgentUtil.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVUserAgentUtil.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVUserAgentUtil.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVTimer.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVTimer.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVTimer.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVConfigParser.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVConfigParser.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVConfigParser.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

CpHeader Classes/Public/CDVViewController.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova/CDVViewController.h
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.h /Users/thali/Github/ThaliTest/platforms/ios/build/device/include/Cordova

ProcessPCH /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch.pch CordovaLib_Prefix.pch normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c-header -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -MD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch.d -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/CordovaLib_Prefix.pch -o /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch.pch --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch.dia

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.o Classes/Public/CDVViewController.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVViewController.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVViewController.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.o Classes/Public/NSDictionary+CordovaPreferences.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSDictionary+CordovaPreferences.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSDictionary+CordovaPreferences.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.o Classes/Public/CDVAppDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVAppDelegate.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVAppDelegate.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewDelegate.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewDelegate.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.o Classes/Public/CDVCommandDelegateImpl.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandDelegateImpl.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandDelegateImpl.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.o Classes/Private/CDVJSON_private.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/CDVJSON_private.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVJSON_private.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.o Classes/Public/CDVWhitelist.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVWhitelist.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVWhitelist.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.o Classes/Public/CDVInvokedUrlCommand.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVInvokedUrlCommand.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVInvokedUrlCommand.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.o Classes/Public/CDVTimer.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVTimer.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVTimer.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.o Classes/Public/CDVUserAgentUtil.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVUserAgentUtil.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUserAgentUtil.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.o Classes/Public/CDVConfigParser.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVConfigParser.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVConfigParser.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.o Classes/Private/Plugins/CDVGestureHandler/CDVGestureHandler.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVGestureHandler/CDVGestureHandler.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVGestureHandler.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.o Classes/Private/Plugins/CDVHandleOpenURL/CDVHandleOpenURL.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVHandleOpenURL/CDVHandleOpenURL.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVHandleOpenURL.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewNavigationDelegate.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewNavigationDelegate.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.o Classes/Public/NSMutableArray+QueueAdditions.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/NSMutableArray+QueueAdditions.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/NSMutableArray+QueueAdditions.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.o Classes/Public/CDVCommandQueue.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVCommandQueue.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVCommandQueue.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.o Classes/Public/CDVPluginResult.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPluginResult.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPluginResult.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.o Classes/Public/CDVPlugin+Resources.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin+Resources.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin+Resources.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.o Classes/Public/CDVURLProtocol.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVURLProtocol.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVURLProtocol.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.o Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewEngine.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVUIWebViewEngine/CDVUIWebViewEngine.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVUIWebViewEngine.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.o Classes/Public/CDVPlugin.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Public/CDVPlugin.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVPlugin.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.o Classes/Private/Plugins/CDVLocalStorage/CDVLocalStorage.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVLocalStorage/CDVLocalStorage.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVLocalStorage.o

CompileC build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.o Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Cordova-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -DDEBUG -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/CordovaLib_Prefix-grvyznvamzynxiarztmfxjlpcuaf/CordovaLib_Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.dia -c /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/Classes/Private/Plugins/CDVIntentAndNavigationFilter/CDVIntentAndNavigationFilter.m -o /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/CDVIntentAndNavigationFilter.o

Libtool /Users/thali/Github/ThaliTest/platforms/ios/build/device/libCordova.a normal armv7
    cd /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib
    export IPHONEOS_DEPLOYMENT_TARGET=8.0
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/libtool -static -arch_only armv7 -syslibroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -L/Users/thali/Github/ThaliTest/platforms/ios/build/device -filelist /Users/thali/Github/ThaliTest/platforms/ios/CordovaLib/build/CordovaLib.build/Debug-iphoneos/CordovaLib.build/Objects-normal/armv7/Cordova.LinkFileList -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/libCordova.a

=== BUILD TARGET ThaliTest OF PROJECT ThaliTest WITH CONFIGURATION Debug ===

Check dependencies

Write auxiliary files
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh
chmod 0755 /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest.hmap
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch.pch.hash-criteria
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/ThaliTest.LinkFileList
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-non-framework-target-headers.hmap
write-file /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap

Create product structure
/bin/mkdir -p /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

PhaseScriptExecution Copy\ www\ directory build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh
    cd /Users/thali/Github/ThaliTest/platforms/ios
    /bin/sh -c /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Script-304B58A110DAC018002A0835.sh

CompileXIB ThaliTest/Classes/MainViewController.xib
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    export XCODE_DEVELOPER_USR_PATH=/Applications/Xcode.app/Contents/Developer/usr/bin/..
    /Applications/Xcode.app/Contents/Developer/usr/bin/ibtool --errors --warnings --notices --module ThaliTest --output-partial-info-plist /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/MainViewController-PartialInfo.plist --auto-activate-custom-fonts --target-device iphone --target-device ipad --minimum-deployment-target 8.0 --output-format human-readable-text --compile /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/MainViewController.nib /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Classes/MainViewController.xib

CpResource cordova/build-release.xcconfig build/device/ThaliTest.app/build-release.xcconfig
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/cordova/build-release.xcconfig /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

CpResource cordova/build.xcconfig build/device/ThaliTest.app/build.xcconfig
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/cordova/build.xcconfig /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

CpResource cordova/build-debug.xcconfig build/device/ThaliTest.app/build-debug.xcconfig
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/cordova/build-debug.xcconfig /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

CpResource ThaliTest/Resources/jxcore_cordova.js build/device/ThaliTest.app/jxcore_cordova.js
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-copy -exclude .DS_Store -exclude CVS -exclude .svn -exclude .git -exclude .hg -resolve-src-symlinks /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Resources/jxcore_cordova.js /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

CompileAssetCatalog build/device/ThaliTest.app ThaliTest/Images.xcassets
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/usr/bin/actool --output-format human-readable-text --notices --warnings --export-dependency-info /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_dependencies --output-partial-info-plist /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_generated_info.plist --app-icon AppIcon --launch-image LaunchImage --compress-pngs --enable-on-demand-resources YES --target-device iphone --target-device ipad --minimum-deployment-target 8.0 --platform iphoneos --compile /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets
/* com.apple.actool.document.notices */
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[iphone][57x57][][][1x]: notice: 57x57 app icons only apply to iPhone apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[iphone][57x57][][][2x]: notice: 57x57@2x app icons only apply to iPhone apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[ipad][50x50][][][1x]: notice: 50x50 iPad spotlight icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[ipad][50x50][][][2x]: notice: 50x50 iPad spotlight icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[ipad][72x72][][][1x]: notice: 72x72 app icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./AppIcon.appiconset/[ipad][72x72][][][2x]: notice: 72x72@2x app icons only apply to iPad apps targeting releases of iOS prior to 7.0
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][736h][3x][portrait][full-screen][8.0]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][736h][3x][landscape][full-screen][8.0]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][667h][2x][portrait][full-screen][8.0]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][][1x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][][2x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[iphone][retina4][2x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[ipad][][1x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Images.xcassets:./LaunchImage.launchimage/[ipad][][2x][portrait][full-screen][]: notice: This launch image only applies to iOS 6.x and prior but the minimum deployment is 7.0 or later.
/* com.apple.actool.compilation-results */
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon57x57.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon57x57@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon60x60@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon60x60@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon29x29@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon40x40@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon50x50~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon50x50@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon72x72~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon72x72@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon76x76~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon76x76@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/AppIcon83.5x83.5@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-800-Portrait-736h@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-800-Landscape-736h@3x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-800-667h@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-568h@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Portrait~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Landscape~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Portrait@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-700-Landscape@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-568h@2x.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-Portrait~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/LaunchImage-Portrait@2x~ipad.png
/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_generated_info.plist


ProcessInfoPlistFile build/device/ThaliTest.app/Info.plist ThaliTest/ThaliTest-Info.plist
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-infoPlistUtility /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/ThaliTest-Info.plist -genpkginfo /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/PkgInfo -expandbuildsettings -format binary -platform iphoneos -additionalcontentfile /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/MainViewController-PartialInfo.plist -additionalcontentfile /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/assetcatalog_generated_info.plist -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/Info.plist

ProcessPCH build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch.pch ThaliTest/ThaliTest-Prefix.pch normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c-header -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -MD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch.d -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/ThaliTest-Prefix.pch -o /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch.pch --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch.dia

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/main.o ThaliTest/main.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/main.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/main.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/main.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/main.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/AppDelegate.o ThaliTest/Classes/AppDelegate.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/AppDelegate.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/AppDelegate.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Classes/AppDelegate.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/AppDelegate.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/MainViewController.o ThaliTest/Classes/MainViewController.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/MainViewController.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/MainViewController.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Classes/MainViewController.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/MainViewController.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/CDVJXcore.o ThaliTest/Plugins/io.jxcore.node/CDVJXcore.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/CDVJXcore.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/CDVJXcore.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/io.jxcore.node/CDVJXcore.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/CDVJXcore.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcore.o ThaliTest/Plugins/io.jxcore.node/JXcore.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcore.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcore.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/io.jxcore.node/JXcore.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcore.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXMobile.o ThaliTest/Plugins/io.jxcore.node/JXMobile.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXMobile.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXMobile.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/io.jxcore.node/JXMobile.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXMobile.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/Reachability.o ThaliTest/Plugins/io.jxcore.node/Reachability.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/Reachability.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/Reachability.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/io.jxcore.node/Reachability.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/Reachability.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcoreExtension.o ThaliTest/Plugins/org.thaliproject.p2p/JXcoreExtension.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcoreExtension.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcoreExtension.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/JXcoreExtension.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/JXcoreExtension.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/NPReachability.o ThaliTest/Plugins/org.thaliproject.p2p/NPReachability.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/NPReachability.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/NPReachability.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/NPReachability.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/NPReachability.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEAppContext.o ThaliTest/Plugins/org.thaliproject.p2p/THEAppContext.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEAppContext.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEAppContext.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEAppContext.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEAppContext.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEPeerBluetooth.o ThaliTest/Plugins/org.thaliproject.p2p/THEPeerBluetooth.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEPeerBluetooth.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEPeerBluetooth.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEPeerBluetooth.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEPeerBluetooth.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerManager.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerManager.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerManager.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerManager.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerManager.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerManager.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClient.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClient.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClient.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClient.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClient.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClient.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServer.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServer.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServer.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServer.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServer.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServer.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerPeerSession.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerPeerSession.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerPeerSession.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerPeerSession.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerPeerSession.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerPeerSession.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSession.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSession.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSession.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSession.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSession.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSession.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServerSession.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSession.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSession.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServerSession.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSession.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerSocketRelay.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerSocketRelay.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerSocketRelay.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerSocketRelay.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerSocketRelay.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerSocketRelay.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSocketRelay.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSocketRelay.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSocketRelay.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSocketRelay.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerClientSocketRelay.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerClientSocketRelay.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSocketRelay.o ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServerSocketRelay.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSocketRelay.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSocketRelay.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServerSocketRelay.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEMultipeerServerSocketRelay.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/GCDAsyncSocket.o ThaliTest/Plugins/org.thaliproject.p2p/GCDAsyncSocket.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/GCDAsyncSocket.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/GCDAsyncSocket.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/GCDAsyncSocket.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/GCDAsyncSocket.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEProtectedMutableDictionary.o ThaliTest/Plugins/org.thaliproject.p2p/THEProtectedMutableDictionary.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEProtectedMutableDictionary.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEProtectedMutableDictionary.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEProtectedMutableDictionary.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THEProtectedMutableDictionary.o

CompileC build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THESessionDictionary.o ThaliTest/Plugins/org.thaliproject.p2p/THESessionDictionary.m normal armv7 objective-c com.apple.compilers.llvm.clang.1_0.compiler
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export LANG=en_US.US-ASCII
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -arch armv7 -fmessage-length=0 -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit=0 -std=c99 -fobjc-arc -fmodules -gmodules -fmodules-prune-interval=86400 -fmodules-prune-after=345600 -fbuild-session-file=/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/C/org.llvm.clang/ModuleCache/Session.modulevalidation -fmodules-validate-once-per-build-session -Wno-trigraphs -fpascal-strings -O0 -Wno-missing-field-initializers -Wno-missing-prototypes -Wno-implicit-atomic-properties -Wno-arc-repeated-use-of-weak -Wduplicate-method-match -Wno-missing-braces -Wparentheses -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion -Wno-shorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector -Wno-strict-selector-match -Wundeclared-selector -Wno-deprecated-implementations -DDEBUG=1 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -miphoneos-version-min=8.0 -g -fvisibility=hidden -Wno-sign-conversion -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-generated-files.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-own-target-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-all-target-headers.hmap -iquote /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest-project-headers.hmap -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device/usr/local/lib/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/UninstalledProducts/iphoneos/include -I/Users/thali/Github/ThaliTest/platforms/ios/build/device -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources/armv7 -I/Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/DerivedSources -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -Werror -include /Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch/ThaliTest-Prefix-gjyteovaxpmddxbkgoythwdmjwlq/ThaliTest-Prefix.pch -MMD -MT dependencies -MF /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THESessionDictionary.d --serialize-diagnostics /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THESessionDictionary.dia -c /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THESessionDictionary.m -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/THESessionDictionary.o

Ld build/device/ThaliTest.app/ThaliTest normal armv7
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export IPHONEOS_DEPLOYMENT_TARGET=8.0
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -arch armv7 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk -L/Users/thali/Github/ThaliTest/platforms/ios/build/device -L/Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/io.jxcore.node -F/Users/thali/Github/ThaliTest/platforms/ios/build/device -filelist /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/ThaliTest.LinkFileList -Xlinker -rpath -Xlinker @executable_path/Frameworks -miphoneos-version-min=8.0 -dead_strip -ObjC -fobjc-arc -fobjc-link-runtime /Users/thali/Github/ThaliTest/platforms/ios/build/device/libCordova.a -lcares -lchrome_zlib -lhttp_parser -ljx -lmozjs -lopenssl -lsqlite3 -luv -lleveldb -lleveldown -lsnappy -framework SystemConfiguration -lstdc++.6.0.9 -framework CFNetwork -framework Foundation -framework Security -framework MultipeerConnectivity -framework CoreBluetooth -Xlinker -dependency_info -Xlinker /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/Objects-normal/armv7/ThaliTest_dependency_info.dat -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/ThaliTest

GenerateDSYMFile build/device/ThaliTest.app.dSYM build/device/ThaliTest.app/ThaliTest
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/dsymutil /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/ThaliTest -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app.dSYM

ProcessProductPackaging /Users/thali/Library/MobileDevice/Provisioning\ Profiles/65137413-edcb-4686-b365-f57b65d65b44.mobileprovision build/device/ThaliTest.app/embedded.mobileprovision
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-productPackagingUtility /Users/thali/Library/MobileDevice/Provisioning\ Profiles/65137413-edcb-4686-b365-f57b65d65b44.mobileprovision -o /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app/embedded.mobileprovision

Touch build/device/ThaliTest.app
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    /usr/bin/touch -c /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app

ProcessProductPackaging /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk/Entitlements.plist build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest.app.xcent
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    builtin-productPackagingUtility /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS9.2.sdk/Entitlements.plist -entitlements -format xml -o /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest.app.xcent

CodeSign build/device/ThaliTest.app
    cd /Users/thali/Github/ThaliTest/platforms/ios
    export CODESIGN_ALLOCATE=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/codesign_allocate
    export PATH="/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/bin:/Users/thali/Library/Android/sdk/build-tools/23.0.2:/usr/bin:/bin:/usr/sbin:/sbin"
    
Signing Identity:     "iPhone Developer: Oguz Bastemur (3QC548Q96Y)"
Provisioning Profile: "iOSTeam Provisioning Profile: *"
                      (65137413-edcb-4686-b365-f57b65d65b44)

    /usr/bin/codesign --force --sign 62C4190333A1793E09EFCD02E217D1FEF0036CEE --entitlements /Users/thali/Github/ThaliTest/platforms/ios/build/ThaliTest.build/Debug-iphoneos/ThaliTest.build/ThaliTest.app.xcent --timestamp=none /Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app
/Users/thali/Github/ThaliTest/platforms/ios/build/device/ThaliTest.app: User interaction is not allowed.
Command /usr/bin/codesign failed with exit code 1

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch GET https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http request GET https://registry.npmjs.org/encodeurl
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/encodeurl
npm http fetch GET https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/escape-html
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/depd
npm http fetch GET https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch GET https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/serve-static
npm http fetch GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/parseurl
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/qs
npm http fetch 200 https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http 304 https://registry.npmjs.org/vary
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http fetch GET https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http fetch GET https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http fetch 200 https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/negotiator
npm http fetch GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http fetch 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http fetch GET https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http fetch 200 https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/statuses
npm http fetch GET https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http fetch GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http fetch GET https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/setprototypeof
npm http 200 https://registry.npmjs.org/inherits
npm http fetch GET https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
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
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/balanced-match
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/es3ify
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/esprima
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/base62
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/iconv-lite
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
npm http request GET https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/object-keys
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
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
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 200 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/base64id
npm http 200 https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 200 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 200 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 200 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 200 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/body-parser
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http 200 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http fetch GET https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http 200 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch GET https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http fetch 200 https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/iconv-lite
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
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
npm http 200 https://registry.npmjs.org/mime-db
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http fetch GET https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
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
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/private
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
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
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
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http 200 https://registry.npmjs.org/duplexify
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http fetch GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http fetch 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http 200 https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http request GET https://registry.npmjs.org/stream-shift
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 200 https://registry.npmjs.org/stream-shift
npm http fetch GET https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/buffer-shims
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/aws4
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/is-typedarray
npm http 200 https://registry.npmjs.org/tough-cookie
npm http fetch GET https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch GET https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http 200 https://registry.npmjs.org/hawk
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http fetch GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/boom
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
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/espree
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/marked
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/catharsis
npm http 200 https://registry.npmjs.org/espree
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http 200 https://registry.npmjs.org/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/tweetnacl
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/jxc
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/unzip
npm http 200 https://registry.npmjs.org/jxc
npm http fetch GET https://registry.npmjs.org/jxc/-/jxc-1.0.15.tgz
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
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
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
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
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
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
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
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/match-stream
npm http request GET https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/binary
npm http 200 https://registry.npmjs.org/setimmediate
npm http 200 https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm http 304 https://registry.npmjs.org/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/proxyquire
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http 200 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/tape
npm http fetch GET https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http fetch GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http fetch GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http 200 https://registry.npmjs.org/request-promise
npm http 200 https://registry.npmjs.org/pouchdb
npm http fetch GET https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/supertest
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/tmp
npm http fetch GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http 200 https://registry.npmjs.org/tape-catch
npm http 200 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http fetch GET https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http fetch 200 https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http 200 https://registry.npmjs.org/nock
npm http fetch 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http fetch GET https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http fetch GET https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch 200 https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
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
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/raw-body
npm http 200 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/range-parser
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/multiparty
npm http fetch GET https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http fetch GET https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 200 https://registry.npmjs.org/compression
npm http 200 https://registry.npmjs.org/cookie-parser
npm http fetch GET https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http 200 https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http fetch GET https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http fetch GET https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http fetch 200 https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http fetch 200 https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/compressible
npm http fetch GET https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch 200 https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/stream-counter
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/argsarray
npm http 200 https://registry.npmjs.org/pouchdb-promise
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
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
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
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/once
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
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/crypto-lite
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 200 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/secure-random
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 200 https://registry.npmjs.org/aproba
npm http fetch GET https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http request GET https://registry.npmjs.org/es6-promise-pool
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 200 https://registry.npmjs.org/es6-promise-pool
npm http fetch GET https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/fruitdown
npm http fetch GET https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http 304 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 200 https://registry.npmjs.org/levelup
npm http fetch GET https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http 200 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http fetch 200 https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 200 https://registry.npmjs.org/vuvuzela
npm http fetch 200 https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http fetch GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http fetch 200 https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 200 https://registry.npmjs.org/sublevel-pouchdb
npm http fetch GET https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
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
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 200 https://registry.npmjs.org/semver
npm http fetch GET https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/level-codec
npm http fetch 200 https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/level-errors
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
npm http 200 https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
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
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 200 https://registry.npmjs.org/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
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
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
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
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/is-array
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http 200 https://registry.npmjs.org/is-array
npm http 304 https://registry.npmjs.org/spark-md5
npm http fetch GET https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http fetch GET https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/extend
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
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
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
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/propagate
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http 200 https://registry.npmjs.org/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http 200 https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http fetch GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http 200 https://registry.npmjs.org/resolve
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/formatio
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
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/arraybuffer.slice
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
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/cookiejar
npm http 200 https://registry.npmjs.org/formidable
npm http 304 https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http 200 https://registry.npmjs.org/has
npm http 200 https://registry.npmjs.org/object-inspect
npm http fetch GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http request GET https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/define-properties
npm http 200 https://registry.npmjs.org/es-abstract
npm http fetch GET https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http fetch 200 https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http request GET https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-symbol
npm http request GET https://registry.npmjs.org/is-date-object
npm http 304 https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/global
npm http 200 https://registry.npmjs.org/global
npm http fetch GET https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http request GET https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/min-document
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
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/encodeurl
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/escape-html
npm http 200 https://registry.npmjs.org/encodeurl
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 200 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/setprototypeof
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/immediate
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
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/commander
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
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/ws
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
npm http 200 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 200 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/javascript-state-machine
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
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/setprototypeof
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
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
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
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
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
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
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
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
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
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
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
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
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/stack-trace
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm JXcore --autoremove [33m./node_modules/thali/node_modules/long/dist/long.min.js.gz[39m
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/proxyquire
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/sinon
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/pouchdb
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/supertest
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tmp
npm http 304 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/basic-auth
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
npm http 304 https://registry.npmjs.org/cookie-parser
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-auth
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/compressible
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/stream-counter
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 200 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 200 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/crypto-lite
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 304 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/map-obj
npm http 304 https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 304 https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 304 https://registry.npmjs.org/aproba
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/es6-promise-pool
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/es6-promise-pool
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 304 https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 304 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/qs
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
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
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/is-array
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 304 https://registry.npmjs.org/is-array
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 304 https://registry.npmjs.org/equals
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
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/propagate
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/chai
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/propagate
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http 200 https://registry.npmjs.org/deep-eql
npm http 304 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/util
npm http 304 https://registry.npmjs.org/samsam
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
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/arraybuffer.slice
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
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 304 https://registry.npmjs.org/superagent
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http 200 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/resumer
npm http 200 https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/define-properties
npm http request GET https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/is-callable
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http 304 https://registry.npmjs.org/is-symbol
npm http request GET https://registry.npmjs.org/global
npm http 304 https://registry.npmjs.org/global
npm http request GET https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/process
npm http 304 https://registry.npmjs.org/process
npm http 304 https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/dom-walk
npm http 304 https://registry.npmjs.org/dom-walk
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
npm JXcore --autoremove [33m./node_modules/long/dist/long.min.js.gz[39m
npm JXcore --autoremove [33m./node_modules/nock/assets/reply_file_2.txt.gz[39m
npm JXcore --autoremove [33m./node_modules/supertest/test/fixtures/test_cert.pem[39m
npm JXcore --autoremove [33m./node_modules/supertest/test/fixtures/test_key.pem[39m
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Could not find service "com.apple.CoreSimulator.CoreSimulatorService" in domain for uid: 501
2016-07-26 11:51:15.619 xcodebuild[4107:9584] launchctl print returned an error code: 28928
2016-07-26 11:51:15.620 xcodebuild[4107:9584] Failed to locate a valid instance of CoreSimulatorService in the bootstrap.  Adding it now.
** BUILD FAILED **


The following build commands failed:
	CodeSign build/device/ThaliTest.app
(1 failure)
Error: Error code 65 for command: xcodebuild with args: -xcconfig,/Users/thali/Github/ThaliTest/platforms/ios/cordova/build-debug.xcconfig,-project,ThaliTest.xcodeproj,ARCHS=armv7 arm64,-target,ThaliTest,-configuration,Debug,-sdk,iphoneos,build,VALID_ARCHS=armv7 arm64,CONFIGURATION_BUILD_DIR=/Users/thali/Github/ThaliTest/platforms/ios/build/device,SHARED_PRECOMPS_DIR=/Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch

```

Error: Command failed: npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http fetch GET https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http fetch GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http 200 https://registry.npmjs.org/express
npm http fetch 200 https://registry.npmjs.org/lie/-/lie-3.0.4.tgz
npm http fetch GET https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/express/-/express-4.14.0.tgz
npm http request GET https://registry.npmjs.org/encodeurl
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/encodeurl
npm http fetch GET https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http 304 https://registry.npmjs.org/content-disposition
npm http 200 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/escape-html
npm http fetch GET https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http 200 https://registry.npmjs.org/depd
npm http fetch GET https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch GET https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/serve-static
npm http fetch GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/range-parser
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/parseurl
npm http 200 https://registry.npmjs.org/utils-merge
npm http 200 https://registry.npmjs.org/qs
npm http fetch 200 https://registry.npmjs.org/encodeurl/-/encodeurl-1.0.1.tgz
npm http 304 https://registry.npmjs.org/vary
npm http fetch 200 https://registry.npmjs.org/content-type/-/content-type-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/cookie/-/cookie-0.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/accepts/-/accepts-1.3.3.tgz
npm http fetch GET https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.5.0.tgz
npm http fetch GET https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http fetch GET https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http fetch GET https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/type-is/-/type-is-1.6.13.tgz
npm http fetch 200 https://registry.npmjs.org/serve-static/-/serve-static-1.11.1.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.14.1.tgz
npm http fetch 200 https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.0.tgz
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/negotiator
npm http fetch GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http fetch 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz
npm http fetch 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.11.tgz
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http fetch GET https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http fetch 200 https://registry.npmjs.org/mime-db/-/mime-db-1.23.0.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/statuses
npm http fetch GET https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/statuses/-/statuses-1.3.0.tgz
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http fetch GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.1.1.tgz
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/destroy
npm http 200 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/mime
npm http fetch GET https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http fetch 200 https://registry.npmjs.org/http-errors/-/http-errors-1.5.0.tgz
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/setprototypeof
npm http 200 https://registry.npmjs.org/inherits
npm http fetch GET https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.0.1.tgz
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http fetch GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http fetch 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.4.tgz
npm http fetch 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.4.tgz
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http fetch GET https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http fetch 200 https://registry.npmjs.org/glob/-/glob-7.0.5.tgz
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/minimatch
npm http 200 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/once
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
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/balanced-match
npm http fetch GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http fetch 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.4.2.tgz
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/es3ify
npm http fetch GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http fetch 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.2.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/esprima
npm http fetch GET https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/jstransform/-/jstransform-11.0.3.tgz
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/base62
npm http fetch GET https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http fetch GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch GET https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch GET https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http 200 https://registry.npmjs.org/source-map
npm http fetch 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1.0-dev-harmony-fb.tgz
npm http fetch 200 https://registry.npmjs.org/base62/-/base62-1.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/object-assign/-/object-assign-2.1.1.tgz
npm http fetch 200 https://registry.npmjs.org/commoner/-/commoner-0.10.4.tgz
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/iconv-lite
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
npm http request GET https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/object-keys
npm http fetch GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http fetch 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.11.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/xtend
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
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 200 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http 200 https://registry.npmjs.org/engine.io
npm http fetch GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.8.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.11.tgz
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/base64id
npm http 200 https://registry.npmjs.org/ws
npm http fetch GET https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/ws/-/ws-1.1.0.tgz
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 200 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 200 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/json3
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/engine.io-client
npm http fetch GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http fetch 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.11.tgz
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 200 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/eyes
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 200 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/body-parser
npm http fetch GET https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http 200 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http fetch GET https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http fetch GET https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http 200 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch GET https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http fetch 200 https://registry.npmjs.org/ip/-/ip-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/body-parser/-/body-parser-1.15.2.tgz
npm http fetch 200 https://registry.npmjs.org/long/-/long-3.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.74.0.tgz
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/iconv-lite
npm http fetch GET https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/raw-body
npm http fetch GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
npm http fetch 200 https://registry.npmjs.org/bytes/-/bytes-2.4.0.tgz
npm http fetch 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.7.tgz
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
npm http 200 https://registry.npmjs.org/mime-db
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http fetch GET https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http fetch 200 https://registry.npmjs.org/send/-/send-0.13.2.tgz
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
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
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http 200 https://registry.npmjs.org/private
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
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
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
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http 200 https://registry.npmjs.org/duplexify
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.1.4.tgz
npm http fetch GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http fetch 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.5.tgz
npm http 200 https://registry.npmjs.org/varint
npm http fetch GET https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/varint/-/varint-4.0.1.tgz
npm http request GET https://registry.npmjs.org/stream-shift
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 200 https://registry.npmjs.org/stream-shift
npm http fetch GET https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/stream-shift/-/stream-shift-1.0.0.tgz
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/buffer-shims
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http fetch GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http fetch GET https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/buffer-shims/-/buffer-shims-1.0.0.tgz
npm http fetch 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.7.tgz
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/bl
npm http 200 https://registry.npmjs.org/aws4
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/is-typedarray
npm http 200 https://registry.npmjs.org/tough-cookie
npm http fetch GET https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch GET https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http 200 https://registry.npmjs.org/http-signature
npm http fetch GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http 200 https://registry.npmjs.org/hawk
npm http fetch GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http fetch 200 https://registry.npmjs.org/bl/-/bl-1.1.2.tgz
npm http fetch 200 https://registry.npmjs.org/aws4/-/aws4-1.4.1.tgz
npm http fetch 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.3.tgz
npm http fetch 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.3.1.tgz
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http fetch GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http fetch 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/boom
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
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/espree
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/marked
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/catharsis
npm http 200 https://registry.npmjs.org/espree
npm http fetch GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http fetch 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.8.tgz
npm http 200 https://registry.npmjs.org/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch GET https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://registry.npmjs.org/wrench/-/wrench-1.5.9.tgz
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/tweetnacl
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.13.3.tgz
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/jxc
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/unzip
npm http 200 https://registry.npmjs.org/jxc
npm http fetch GET https://registry.npmjs.org/jxc/-/jxc-1.0.15.tgz
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
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/commoner
npm http 200 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/acorn
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
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
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
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http fetch GET https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/qs/-/qs-6.2.1.tgz
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
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
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/match-stream
npm http request GET https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/binary
npm http 200 https://registry.npmjs.org/setimmediate
npm http 200 https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs v3.0.0 and before will fail on node releases >= v7.0. Please update to graceful-fs@^4.0.0 as soon as possible. Use 'npm ls graceful-fs' to find it in the tree.
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm http 304 https://registry.npmjs.org/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/proxyquire
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/socket.io-client
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http 200 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/tape
npm http fetch GET https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http fetch GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http fetch GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http 200 https://registry.npmjs.org/request-promise
npm http 200 https://registry.npmjs.org/pouchdb
npm http fetch GET https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/supertest
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/tmp
npm http fetch GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http 200 https://registry.npmjs.org/tape-catch
npm http 200 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http fetch GET https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.11.5.tgz
npm http fetch 200 https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.10.tgz
npm http 200 https://registry.npmjs.org/nock
npm http fetch 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.5.tgz
npm http fetch 200 https://registry.npmjs.org/tape/-/tape-4.6.0.tgz
npm http fetch GET https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.6.tgz
npm http fetch 200 https://registry.npmjs.org/sinon/-/sinon-1.17.4.tgz
npm http fetch GET https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.4.5.tgz
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch 200 https://registry.npmjs.org/uuid/-/uuid-2.0.2.tgz
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
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/raw-body
npm http 200 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/range-parser
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/multiparty
npm http fetch GET https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http fetch GET https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 200 https://registry.npmjs.org/compression
npm http 200 https://registry.npmjs.org/cookie-parser
npm http fetch GET https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http 200 https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http fetch GET https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http fetch GET https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http fetch 200 https://registry.npmjs.org/bluebird/-/bluebird-3.4.1.tgz
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http fetch 200 https://registry.npmjs.org/compression/-/compression-1.6.2.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.1.0.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.10.2.tgz
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/compressible
npm http fetch GET https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http fetch 200 https://registry.npmjs.org/compressible/-/compressible-2.0.8.tgz
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/stream-counter
npm http fetch GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http fetch 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.1.14.tgz
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/argsarray
npm http 200 https://registry.npmjs.org/pouchdb-promise
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
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
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
npm http request GET https://registry.npmjs.org/object-assign
npm http request GET https://registry.npmjs.org/commoner
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/commoner
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/once
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
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/crypto-lite
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 200 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/secure-random
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/camelcase-keys
npm http 200 https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http 200 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/repeating
npm http 200 https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 200 https://registry.npmjs.org/aproba
npm http fetch GET https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http fetch 200 https://registry.npmjs.org/aproba/-/aproba-1.0.4.tgz
npm http request GET https://registry.npmjs.org/es6-promise-pool
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 200 https://registry.npmjs.org/es6-promise-pool
npm http fetch GET https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/fruitdown
npm http fetch GET https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http 304 https://registry.npmjs.org/request
npm http fetch GET https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 200 https://registry.npmjs.org/levelup
npm http fetch GET https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http 200 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http fetch 200 https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.2.tgz
npm http 200 https://registry.npmjs.org/vuvuzela
npm http fetch 200 https://registry.npmjs.org/js-extend/-/js-extend-0.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/request/-/request-2.72.0.tgz
npm http fetch GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http fetch 200 https://registry.npmjs.org/levelup/-/levelup-1.3.2.tgz
npm http 200 https://registry.npmjs.org/sublevel-pouchdb
npm http fetch GET https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.3.tgz
npm http fetch 200 https://registry.npmjs.org/sublevel-pouchdb/-/sublevel-pouchdb-1.0.1.tgz
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
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 200 https://registry.npmjs.org/semver
npm http fetch GET https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/level-codec
npm http fetch 200 https://registry.npmjs.org/semver/-/semver-5.1.1.tgz
npm http 304 https://registry.npmjs.org/level-errors
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
npm http 200 https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
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
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 200 https://registry.npmjs.org/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
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
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
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
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/is-array
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http fetch GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http 200 https://registry.npmjs.org/is-array
npm http 304 https://registry.npmjs.org/spark-md5
npm http fetch GET https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-5.4.0.tgz
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http fetch GET https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/is-array/-/is-array-1.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-2.0.2.tgz
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/extend
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
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
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
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/propagate
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http 200 https://registry.npmjs.org/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http 200 https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http fetch GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http fetch 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.2.tgz
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http 200 https://registry.npmjs.org/resolve
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/formatio
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
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/arraybuffer.slice
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
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/extend
npm http 200 https://registry.npmjs.org/cookiejar
npm http 200 https://registry.npmjs.org/formidable
npm http 304 https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http 200 https://registry.npmjs.org/has
npm http 200 https://registry.npmjs.org/object-inspect
npm http fetch GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http fetch 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.2.1.tgz
npm http request GET https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/define-properties
npm http 200 https://registry.npmjs.org/es-abstract
npm http fetch GET https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http fetch 200 https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.1.tgz
npm http request GET https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-symbol
npm http request GET https://registry.npmjs.org/is-date-object
npm http 304 https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/global
npm http 200 https://registry.npmjs.org/global
npm http fetch GET https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http fetch 200 https://registry.npmjs.org/global/-/global-4.3.0.tgz
npm http request GET https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/min-document
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
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/encodeurl
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/escape-html
npm http 200 https://registry.npmjs.org/encodeurl
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 200 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/setprototypeof
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/fs.realpath
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/fs.realpath
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/immediate
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
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/detective
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/commander
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
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/ws
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
npm http 200 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/cycle
npm http 200 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/deep-equal
npm http 200 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/javascript-state-machine
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
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/setprototypeof
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/setprototypeof
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
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
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
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
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/q
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/detective
npm http 304 https://registry.npmjs.org/mkdirp
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
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
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
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/stream-shift
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/buffer-shims
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/buffer-shims
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
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
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
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
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/getpass
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/getpass
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/stack-trace
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm JXcore --autoremove [33m./node_modules/thali/node_modules/long/dist/long.min.js.gz[39m
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/proxyquire
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/sinon
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/pouchdb
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/supertest
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tmp
npm http 304 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/basic-auth
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
npm http 304 https://registry.npmjs.org/cookie-parser
npm http 200 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-auth
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/compressible
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/stream-counter
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 200 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/secure-random
npm http 200 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/crypto-lite
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 304 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/indent-string
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/map-obj
npm http 304 https://registry.npmjs.org/map-obj
npm http 200 https://registry.npmjs.org/camelcase
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 304 https://registry.npmjs.org/get-stdin
npm http 200 https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 304 https://registry.npmjs.org/aproba
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/es6-promise-pool
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/es6-promise-pool
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 304 https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 304 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/qs
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
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
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/is-array
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 304 https://registry.npmjs.org/is-array
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/couchdb-render
npm http request GET https://registry.npmjs.org/couchdb-resp-completer
npm http 304 https://registry.npmjs.org/couchdb-resp-completer
npm http request GET https://registry.npmjs.org/equals
npm http 304 https://registry.npmjs.org/equals
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
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/propagate
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/chai
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/propagate
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http 200 https://registry.npmjs.org/deep-eql
npm http 304 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/type-detect
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 200 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/util
npm http 304 https://registry.npmjs.org/samsam
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
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/arraybuffer.slice
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
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 304 https://registry.npmjs.org/superagent
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/qs
npm http 200 https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http 200 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/resumer
npm http 200 https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/define-properties
npm http request GET https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/is-callable
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http 304 https://registry.npmjs.org/is-symbol
npm http request GET https://registry.npmjs.org/global
npm http 304 https://registry.npmjs.org/global
npm http request GET https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/process
npm http 304 https://registry.npmjs.org/process
npm http 304 https://registry.npmjs.org/min-document
npm http request GET https://registry.npmjs.org/dom-walk
npm http 304 https://registry.npmjs.org/dom-walk
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
npm JXcore --autoremove [33m./node_modules/long/dist/long.min.js.gz[39m
npm JXcore --autoremove [33m./node_modules/nock/assets/reply_file_2.txt.gz[39m
npm JXcore --autoremove [33m./node_modules/supertest/test/fixtures/test_cert.pem[39m
npm JXcore --autoremove [33m./node_modules/supertest/test/fixtures/test_key.pem[39m
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Note: Some input files use or override a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Could not find service "com.apple.CoreSimulator.CoreSimulatorService" in domain for uid: 501
2016-07-26 11:51:15.619 xcodebuild[4107:9584] launchctl print returned an error code: 28928
2016-07-26 11:51:15.620 xcodebuild[4107:9584] Failed to locate a valid instance of CoreSimulatorService in the bootstrap.  Adding it now.
** BUILD FAILED **


The following build commands failed:
	CodeSign build/device/ThaliTest.app
(1 failure)
Error: Error code 65 for command: xcodebuild with args: -xcconfig,/Users/thali/Github/ThaliTest/platforms/ios/cordova/build-debug.xcconfig,-project,ThaliTest.xcodeproj,ARCHS=armv7 arm64,-target,ThaliTest,-configuration,Debug,-sdk,iphoneos,build,VALID_ARCHS=armv7 arm64,CONFIGURATION_BUILD_DIR=/Users/thali/Github/ThaliTest/platforms/ios/build/device,SHARED_PRECOMPS_DIR=/Users/thali/Github/ThaliTest/platforms/ios/build/sharedpch
