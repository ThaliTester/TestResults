#### Test (Fail) 63980877 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   3799dbd..7da7b77  vNext_yarong_664 -> origin/vNext_yarong_664

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '7da7b77'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 7da7b77... Temporarily filter out test that fails with PSK

```

```
Cordova version:
6.1.0
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├─┬ express@4.13.4 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.10 
│ │ │ └── mime-db@1.22.0 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.1 
│ ├── content-type@1.0.1 
│ ├── cookie@0.1.5 
│ ├── cookie-signature@1.0.6 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.1.0 
│ ├── escape-html@1.0.3 
│ ├── etag@1.7.0 
│ ├─┬ finalhandler@0.4.1 
│ │ └── unpipe@1.0.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.1 
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
│ ├─┬ send@0.13.1 
│ │ ├── destroy@1.0.4 
│ │ ├─┬ http-errors@1.3.1 
│ │ │ └── inherits@2.0.1 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├── serve-static@1.10.2 
│ ├─┬ type-is@1.6.12 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.1 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.24.0 
│   ├── graceful-fs@4.1.3 
│   ├── jsonfile@2.2.3 
│   ├── path-is-absolute@1.0.0 
│   └─┬ rimraf@2.5.2 
│     └─┬ glob@7.0.3 
│       ├─┬ inflight@1.0.4 
│       │ └── wrappy@1.0.1 
│       ├─┬ minimatch@3.0.0 
│       │ └─┬ brace-expansion@1.1.3 
│       │   ├── balanced-match@0.3.0 
│       │   └── concat-map@0.0.1 
│       └── once@1.3.3 
├─┬ lie@3.0.2 
│ ├─┬ es3ify@0.1.4 
│ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ └─┬ jstransform@3.0.0 
│ │   ├── base62@0.1.1 
│ │   └─┬ source-map@0.1.31 
│ │     └── amdefine@1.0.0 
│ ├── immediate@3.0.5 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
│ │ └─┬ through2@0.6.5 
│ │   ├─┬ readable-stream@1.0.33 
│ │   │ ├── core-util-is@1.0.2 
│ │   │ └── string_decoder@0.10.31 
│ │   └── xtend@4.0.1 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.0 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.3 
├── node-uuid@1.4.7 
├─┬ socket.io@1.4.5 
│ ├─┬ engine.io@1.6.8 
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
│ │ └─┬ ws@1.0.1 
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
├─┬ socket.io-client@1.4.5 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.2.0 
│ ├─┬ engine.io-client@1.6.8 
│ │ ├── component-inherit@0.0.3 
│ │ ├── has-cors@1.1.0 
│ │ ├── parsejson@0.0.1 
│ │ ├── parseqs@0.0.2 
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
├─┬ body-parser@1.15.0 
│ ├── bytes@2.2.0 
│ ├── content-type@1.0.1 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.1.0 
│ ├─┬ http-errors@1.4.0 
│ │ └── statuses@1.2.1 
│ ├── iconv-lite@0.4.13 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@6.1.0 
│ ├─┬ raw-body@2.1.6 
│ │ ├── bytes@2.3.0 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.12 
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
│ │ └── mime@1.3.4 
│ ├─┬ serve-static@1.10.2 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.1 
│ │   ├── destroy@1.0.4 
│ │   └── http-errors@1.3.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├── ip@1.1.2 
├── javascript-state-machine@2.3.5 
├─┬ jsdoc@3.4.0 
│ ├── async@1.4.2 
│ ├── bluebird@2.9.34 
│ ├─┬ catharsis@0.8.7 
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
│ └── wrench@1.5.8 
├─┬ lie@3.0.2 
│ ├─┬ es3ify@0.1.4 
│ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ ├─┬ jstransform@3.0.0 
│ │ │ ├── base62@0.1.1 
│ │ │ └─┬ source-map@0.1.31 
│ │ │   └── amdefine@1.0.0 
│ │ └── through@2.3.8 
│ ├── immediate@3.0.5 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ ├── isarray@0.0.1 
│ │ │ └── object-keys@1.0.9 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.33 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.0 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.3 
├── long@3.0.3 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.3 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └─┬ once@1.3.3 
│ │ │   └── wrappy@1.0.1 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── inherits@2.0.1 
│ ├─┬ readable-stream@2.0.6 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.6 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ ├── varint@4.0.0 
│ └── xtend@4.0.1 
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
├── node-uuid@1.4.7 
├─┬ request@2.69.0 
│ ├── aws-sign2@0.6.0 
│ ├─┬ aws4@1.3.2 
│ │ └─┬ lru-cache@4.0.1 
│ │   ├── pseudomap@1.0.2 
│ │   └── yallist@2.0.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
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
│ │ └─┬ pinkie-promise@2.0.0 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.2.2 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.2 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.7.4 
│ │   ├── asn1@0.2.3 
│ │   └─┬ dashdash@1.13.0 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.10 
│ │ └── mime-db@1.22.0 
│ ├── oauth-sign@0.8.1 
│ ├── qs@6.0.2 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.2 
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
└─┬ request@2.69.0
  └─┬ http-signature@1.1.1
    └─┬ sshpk@1.7.4
      ├── ecc-jsbn@0.1.1 
      ├── jodid25519@1.0.2 
      ├── jsbn@0.1.0 
      └── tweetnacl@0.14.3 

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├─┬ fs-extra-promise@0.2.1 
│ ├── bluebird@2.10.2 
│ └─┬ fs-extra@0.24.0 
│   ├── graceful-fs@4.1.3 
│   ├── jsonfile@2.2.3 
│   ├── path-is-absolute@1.0.0 
│   └─┬ rimraf@2.5.2 
│     └─┬ glob@7.0.3 
│       ├─┬ inflight@1.0.4 
│       │ └── wrappy@1.0.1 
│       ├─┬ minimatch@3.0.0 
│       │ └─┬ brace-expansion@1.1.3 
│       │   ├── balanced-match@0.3.0 
│       │   └── concat-map@0.0.1 
│       └── once@1.3.3 
├─┬ jxc@1.0.14 
│ └─┬ jxtools@0.0.4  (git+https://github.com/ktrzeciaknubisa/jxtools.git#644cf31ea259cb65a97e5c3ed5ea1236dba298a3)
│   ├── adm-zip@0.4.7 
│   └── progress@1.1.8 
├─┬ lie@3.0.2 
│ ├─┬ es3ify@0.1.4 
│ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ ├─┬ jstransform@3.0.0 
│ │ │ ├── base62@0.1.1 
│ │ │ └─┬ source-map@0.1.31 
│ │ │   └── amdefine@1.0.0 
│ │ └── through@2.3.8 
│ ├── immediate@3.0.5 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
│ │ └─┬ through2@0.6.5 
│ │   └── xtend@4.0.1 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.0 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.3 
├─┬ request@2.69.0 
│ ├── aws-sign2@0.6.0 
│ ├─┬ aws4@1.3.2 
│ │ └─┬ lru-cache@4.0.1 
│ │   ├── pseudomap@1.0.2 
│ │   └── yallist@2.0.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   ├── isarray@1.0.0 
│ │   ├── process-nextick-args@1.0.6 
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
│ │ └─┬ pinkie-promise@2.0.0 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.2.2 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.2 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.7.4 
│ │   ├── asn1@0.2.3 
│ │   ├─┬ dashdash@1.13.0 
│ │   │ └── assert-plus@1.0.0 
│ │   ├── ecc-jsbn@0.1.1 
│ │   ├── jodid25519@1.0.2 
│ │   ├── jsbn@0.1.0 
│ │   └── tweetnacl@0.14.3 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.10 
│ │ └── mime-db@1.22.0 
│ ├── node-uuid@1.4.7 
│ ├── oauth-sign@0.8.1 
│ ├── qs@6.0.2 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.2 
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
  ├─┬ readable-stream@1.0.33 
  │ ├── core-util-is@1.0.2 
  │ ├── isarray@0.0.1 
  │ └── string_decoder@0.10.31 
  └── setimmediate@1.0.4 

/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali -> /usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali

> sqlite3@3.1.2 install /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sqlite3
> node-pre-gyp install --fallback-to-build

Target arch x64
  ACTION deps_sqlite3_gyp_action_before_build_target_unpack_sqlite_dep Release/obj/gen/sqlite-autoconf-3090100/sqlite3.c
  TOUCH Release/obj.target/deps/action_before_build.stamp
  CC(target) Release/obj.target/sqlite3/gen/sqlite-autoconf-3090100/sqlite3.o
  LIBTOOL-STATIC Release/sqlite3.a
  CXX(target) Release/obj.target/node_sqlite3/src/database.o
  CXX(target) Release/obj.target/node_sqlite3/src/node_sqlite3.o
  CXX(target) Release/obj.target/node_sqlite3/src/statement.o
  SOLINK_MODULE(target) Release/node_sqlite3.node
  COPY /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/sqlite3/lib/binding/node-v11-darwin-x64/node_sqlite3.node
  TOUCH Release/obj.target/action_after_build.stamp

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
├── bn.js@4.11.1 
├─┬ body-parser@1.15.0 
│ ├── bytes@2.2.0 
│ ├── content-type@1.0.1 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.1.0 
│ ├─┬ http-errors@1.4.0 
│ │ └── statuses@1.2.1 
│ ├── iconv-lite@0.4.13 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@6.1.0 
│ ├─┬ raw-body@2.1.6 
│ │ ├── bytes@2.3.0 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.12 
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
│ │ └── mime@1.3.4 
│ ├─┬ serve-static@1.10.2 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.1 
│ │   ├── destroy@1.0.4 
│ │   └── http-errors@1.3.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ express-pouchdb@1.0.3 
│ ├── basic-auth@1.0.3 
│ ├── bluebird@2.10.2 
│ ├─┬ compression@1.6.1 
│ │ ├─┬ accepts@1.3.2 
│ │ │ └── negotiator@0.6.0 
│ │ ├── compressible@2.0.7 
│ │ ├── on-headers@1.0.1 
│ │ └── vary@1.1.0 
│ ├─┬ cookie-parser@1.4.1 
│ │ └── cookie@0.2.3 
│ ├── extend@1.3.0 
│ ├── header-case-normalizer@1.0.3 
│ ├─┬ multiparty@3.3.2 
│ │ ├── readable-stream@1.1.13 
│ │ └── stream-counter@0.2.0 
│ ├── node-uuid@1.4.1 
│ ├─┬ pouchdb-all-dbs@1.0.1 
│ │ ├─┬ lie@2.9.1 
│ │ │ └── unreachable-branch-transform@0.2.3 
│ │ └── tiny-queue@0.2.1 
│ ├─┬ pouchdb-auth@2.0.1 
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
│ │ │ └── aproba@1.0.1 
│ │ ├── crypto-lite@0.1.0 
│ │ ├── pouchdb-bulkdocs-wrapper@1.0.2 
│ │ ├── pouchdb-plugin-error@1.0.1 
│ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ ├── bluebird@1.2.4 
│ │ │ └── lie@2.7.7 
│ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │   └── xmlhttprequest@1.8.0 
│ │ ├── pouchdb-system-db@1.0.4 
│ │ ├── promise-nodify@1.0.2 
│ │ └── secure-random@1.1.1 
│ ├─┬ pouchdb-find@0.1.0 
│ │ ├─┬ jshint@2.9.1 
│ │ │ ├─┬ cli@0.6.6 
│ │ │ │ └─┬ glob@3.2.11 
│ │ │ │   └─┬ minimatch@0.3.0 
│ │ │ │     ├── lru-cache@2.7.3 
│ │ │ │     └── sigmund@1.0.1 
│ │ │ ├─┬ console-browserify@1.1.0 
│ │ │ │ └── date-now@0.1.4 
│ │ │ ├── exit@0.1.2 
│ │ │ ├─┬ htmlparser2@3.8.3 
│ │ │ │ ├── domelementtype@1.3.0 
│ │ │ │ ├── domhandler@2.3.0 
│ │ │ │ ├─┬ domutils@1.5.1 
│ │ │ │ │ └─┬ dom-serializer@0.1.0 
│ │ │ │ │   ├── domelementtype@1.1.3 
│ │ │ │ │   └── entities@1.1.1 
│ │ │ │ └── entities@1.0.0 
│ │ │ ├── lodash@3.7.0 
│ │ │ ├── shelljs@0.3.0 
│ │ │ └── strip-json-comments@1.0.4 
│ │ ├── lie@2.9.1 
│ │ ├─┬ pouchdb-abstract-mapreduce@0.2.2 
│ │ │ ├── lie@2.9.1 
│ │ │ └── spark-md5@0.0.5 
│ │ ├── pouchdb-extend@0.1.2 
│ │ ├─┬ pouchdb-upsert@1.1.3 
│ │ │ └── lie@2.9.1 
│ │ └── spark-md5@0.0.5 
│ ├─┬ pouchdb-list@1.1.0 
│ │ ├─┬ couchdb-objects@1.0.7 
│ │ │ └── is-empty@0.0.1 
│ │ ├── couchdb-render@1.0.1 
│ │ └── extend@3.0.0 
│ ├─┬ pouchdb-replicator@2.1.3 
│ │ ├─┬ equals@1.0.1 
│ │ │ └── jkroso-type@1.1.1 
│ │ └── random-uuid-v4@0.0.4 
│ ├─┬ pouchdb-rewrite@1.0.7 
│ │ └── pouchdb-route@1.0.3 
│ ├─┬ pouchdb-security@1.2.6 
│ │ └── pouchdb-changeslike-wrapper@1.0.1 
│ ├── pouchdb-show@1.0.8 
│ ├─┬ pouchdb-size@1.2.2 
│ │ └─┬ get-folder-size@0.1.1 
│ │   ├── async@0.9.2 
│ │   └── minimist@0.1.0 
│ ├─┬ pouchdb-update@1.0.8 
│ │ ├── couchdb-eval@1.0.6 
│ │ └── couchdb-resp-completer@1.0.3 
│ ├── pouchdb-validation@1.2.1 
│ ├── pouchdb-vhost@1.0.2 
│ ├── pouchdb-wrappers@1.3.6 
│ └─┬ raw-body@1.3.4 
│   ├── bytes@1.0.0 
│   └── iconv-lite@0.4.8 
├─┬ fs-extra-promise@0.2.1 
│ └─┬ fs-extra@0.24.0 
│   ├── graceful-fs@4.1.3 
│   ├── jsonfile@2.2.3 
│   ├── path-is-absolute@1.0.0 
│   └─┬ rimraf@2.5.2 
│     └── glob@7.0.3 
├── is-property@1.0.2 
├─┬ leveldown-mobile@1.1.1 
│ ├── abstract-leveldown@2.1.4 
│ ├── bindings@1.2.1 
│ └── fast-future@1.0.1 
├─┬ lie@3.0.2 
│ ├─┬ es3ify@0.1.4 
│ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ └─┬ jstransform@3.0.0 
│ │   ├── base62@0.1.1 
│ │   └─┬ source-map@0.1.31 
│ │     └── amdefine@1.0.0 
│ ├─┬ immediate@3.0.5 
│ │ └── unreachable-branch-transform@0.3.0 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.9 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.33 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.0 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.3 
├── long@3.0.3 
├── minimist@1.2.0 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.3 
│ │ ├── end-of-stream@1.0.0 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── inherits@2.0.1 
│ ├─┬ readable-stream@2.0.6 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.6 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ ├── varint@4.0.0 
│ └── xtend@4.0.1 
├─┬ nock@2.18.2 
│ ├─┬ chai@3.5.0 
│ │ ├── assertion-error@1.0.1 
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
│ └── ip@1.1.2 
├── node-uuid@1.4.7 
├─┬ pouchdb@5.3.1 
│ ├── argsarray@0.0.1 
│ ├── double-ended-queue@2.0.0-0 
│ ├─┬ es3ify@0.2.1 
│ │ └── esprima@2.7.2 
│ ├─┬ fruitdown@1.0.2 
│ │ ├─┬ abstract-leveldown@0.12.3 
│ │ │ └── xtend@3.0.0 
│ │ ├── d64@1.0.0 
│ │ └── tiny-queue@0.2.0 
│ ├── js-extend@1.0.1 
│ ├─┬ level-write-stream@1.0.0 
│ │ └─┬ end-stream@0.1.0 
│ │   └─┬ write-stream@0.4.3 
│ │     └── readable-stream@0.0.4 
│ ├─┬ levelup@1.3.1 
│ │ ├─┬ deferred-leveldown@1.2.1 
│ │ │ └── abstract-leveldown@2.4.1 
│ │ ├── level-codec@6.1.0 
│ │ ├── level-errors@1.0.4 
│ │ ├── level-iterator-stream@1.3.1 
│ │ ├── prr@1.0.1 
│ │ └── semver@5.1.0 
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
│ ├── scope-eval@0.0.3 
│ ├── spark-md5@2.0.2 
│ ├─┬ sublevel-pouchdb@1.0.0 
│ │ ├─┬ errno@0.1.4 
│ │ │ └── prr@0.0.0 
│ │ ├── ltgt@2.1.2 
│ │ ├─┬ pull-stream@2.21.0 
│ │ │ └── pull-core@1.0.0 
│ │ └── readable-stream@1.0.33 
│ ├─┬ through2@2.0.1 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── vuvuzela@1.0.2 
│ └─┬ websql@0.1.0 
│   ├── immediate@3.2.2 
│   ├── noop-fn@1.0.0 
│   └─┬ sqlite3@3.1.2 
│     ├── nan@2.2.0 
│     └─┬ node-pre-gyp@0.6.24
│       ├─┬ mkdirp@0.5.1 
│       │ └── minimist@0.0.8 
│       ├─┬ npmlog@2.0.3
│       │ └─┬ are-we-there-yet@1.1.2
│       │   └─┬ readable-stream@2.0.6 
│       │     ├── core-util-is@1.0.2 
│       │     ├── inherits@2.0.1 
│       │     ├── isarray@1.0.0 
│       │     ├── process-nextick-args@1.0.6 
│       │     ├── string_decoder@0.10.31 
│       │     └── util-deprecate@1.0.2 
│       ├─┬ rc@1.1.6
│       │ ├── minimist@1.2.0 
│       │ └── strip-json-comments@1.0.4 
│       ├─┬ request@2.69.0 
│       │ ├── aws-sign2@0.6.0 
│       │ ├─┬ aws4@1.3.2 
│       │ │ └─┬ lru-cache@4.0.0
│       │ │   ├── pseudomap@1.0.2 
│       │ │   └── yallist@2.0.0 
│       │ ├─┬ bl@1.0.3 
│       │ │ └─┬ readable-stream@2.0.6 
│       │ │   ├── core-util-is@1.0.2 
│       │ │   ├── inherits@2.0.1 
│       │ │   ├── isarray@1.0.0 
│       │ │   ├── process-nextick-args@1.0.6 
│       │ │   ├── string_decoder@0.10.31 
│       │ │   └── util-deprecate@1.0.2 
│       │ ├── caseless@0.11.0 
│       │ ├─┬ combined-stream@1.0.5 
│       │ │ └── delayed-stream@1.0.0 
│       │ ├── extend@3.0.0 
│       │ ├── forever-agent@0.6.1 
│       │ ├─┬ form-data@1.0.0-rc4 
│       │ │ └── async@1.5.2 
│       │ ├─┬ har-validator@2.0.6 
│       │ │ ├─┬ chalk@1.1.1
│       │ │ │ ├── escape-string-regexp@1.0.5 
│       │ │ │ ├─┬ has-ansi@2.0.0 
│       │ │ │ │ └── ansi-regex@2.0.0 
│       │ │ │ ├─┬ strip-ansi@3.0.1 
│       │ │ │ │ └── ansi-regex@2.0.0 
│       │ │ │ └── supports-color@2.0.0 
│       │ │ ├─┬ commander@2.9.0 
│       │ │ │ └── graceful-readlink@1.0.1 
│       │ │ ├─┬ is-my-json-valid@2.13.1 
│       │ │ │ ├── generate-function@2.0.0 
│       │ │ │ ├─┬ generate-object-property@1.2.0 
│       │ │ │ │ └── is-property@1.0.2 
│       │ │ │ ├── jsonpointer@2.0.0 
│       │ │ │ └── xtend@4.0.1 
│       │ │ └─┬ pinkie-promise@2.0.0 
│       │ │   └── pinkie@2.0.4 
│       │ ├─┬ hawk@3.1.3 
│       │ │ ├── boom@2.10.1 
│       │ │ ├── cryptiles@2.0.5 
│       │ │ ├── hoek@2.16.3 
│       │ │ └── sntp@1.0.9 
│       │ ├─┬ http-signature@1.1.1 
│       │ │ ├── assert-plus@0.2.0 
│       │ │ ├─┬ jsprim@1.2.2 
│       │ │ │ ├── extsprintf@1.0.2 
│       │ │ │ ├── json-schema@0.2.2 
│       │ │ │ └── verror@1.3.6 
│       │ │ └─┬ sshpk@1.7.4 
│       │ │   ├── asn1@0.2.3 
│       │ │   └─┬ dashdash@1.13.0 
│       │ │     └── assert-plus@1.0.0 
│       │ ├── is-typedarray@1.0.0 
│       │ ├── isstream@0.1.2 
│       │ ├── json-stringify-safe@5.0.1 
│       │ ├─┬ mime-types@2.1.10 
│       │ │ └── mime-db@1.22.0 
│       │ ├── node-uuid@1.4.7 
│       │ ├── oauth-sign@0.8.1 
│       │ ├── qs@6.0.2 
│       │ ├── stringstream@0.0.5 
│       │ ├── tough-cookie@2.2.2 
│       │ └── tunnel-agent@0.4.2 
│       ├─┬ rimraf@2.5.2 
│       │ └─┬ glob@7.0.3 
│       │   ├─┬ inflight@1.0.4 
│       │   │ └── wrappy@1.0.1 
│       │   ├── inherits@2.0.1 
│       │   ├─┬ minimatch@3.0.0
│       │   │ └─┬ brace-expansion@1.1.3 
│       │   │   ├── balanced-match@0.3.0 
│       │   │   └── concat-map@0.0.1 
│       │   ├─┬ once@1.3.3 
│       │   │ └── wrappy@1.0.1 
│       │   └── path-is-absolute@1.0.0 
│       ├── semver@5.1.0 
│       ├─┬ tar@2.2.1
│       │ ├─┬ fstream@1.0.8
│       │ │ └── graceful-fs@4.1.3 
│       │ └── inherits@2.0.1 
│       └─┬ tar-pack@3.1.3
│         ├─┬ debug@2.2.0 
│         │ └── ms@0.7.1 
│         ├─┬ fstream@1.0.8
│         │ ├── graceful-fs@4.1.3 
│         │ └── inherits@2.0.1 
│         ├─┬ fstream-ignore@1.0.3
│         │ ├── inherits@2.0.1 
│         │ └─┬ minimatch@3.0.0
│         │   └─┬ brace-expansion@1.1.3 
│         │     ├── balanced-match@0.3.0 
│         │     └── concat-map@0.0.1 
│         ├─┬ once@1.3.3 
│         │ └── wrappy@1.0.1 
│         └─┬ readable-stream@2.0.6 
│           ├── core-util-is@1.0.2 
│           ├── inherits@2.0.1 
│           ├── isarray@1.0.0 
│           ├── process-nextick-args@1.0.6 
│           ├── string_decoder@0.10.31 
│           └── util-deprecate@1.0.2 
├─┬ proxyquire@1.7.4 
│ ├─┬ fill-keys@1.0.2 
│ │ └── is-object@1.0.1 
│ └── module-not-found-error@1.0.1 
├─┬ randomstring@1.1.4 
│ └── array-uniq@1.0.2 
├─┬ request@2.69.0 
│ ├── aws-sign2@0.6.0 
│ ├─┬ aws4@1.3.2 
│ │ └─┬ lru-cache@4.0.1 
│ │   ├── pseudomap@1.0.2 
│ │   └── yallist@2.0.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├── forever-agent@0.6.1 
│ ├─┬ form-data@1.0.0-rc4 
│ │ └── async@1.5.2 
│ ├─┬ har-validator@2.0.6 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ ├─┬ is-my-json-valid@2.13.1 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├── generate-object-property@1.2.0 
│ │ │ └── jsonpointer@2.0.0 
│ │ └─┬ pinkie-promise@2.0.0 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.2.2 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.2 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.7.4 
│ │   ├── asn1@0.2.3 
│ │   └─┬ dashdash@1.13.0 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.10 
│ │ └── mime-db@1.22.0 
│ ├── oauth-sign@0.8.1 
│ ├── qs@6.0.2 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.2 
├─┬ request-promise@0.4.3 
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
├─┬ socket.io-client@1.4.5 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.2.0 
│ ├─┬ engine.io-client@1.6.8 
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
├── supertest-as-promised@2.0.2 
├─┬ tape@4.5.1 
│ ├── defined@1.0.0 
│ ├── function-bind@1.1.0 
│ ├─┬ glob@7.0.3 
│ │ ├─┬ inflight@1.0.4 
│ │ │ └── wrappy@1.0.1 
│ │ ├─┬ minimatch@2.0.10 
│ │ │ └─┬ brace-expansion@1.1.3 
│ │ │   └── balanced-match@0.3.0 
│ │ └── once@1.3.3 
│ ├── has@1.0.1 
│ ├── object-inspect@1.1.0 
│ ├── resolve@1.1.7 
│ ├── resumer@0.0.0 
│ ├─┬ string.prototype.trim@1.1.2 
│ │ ├── define-properties@1.1.2 
│ │ └─┬ es-abstract@1.5.0 
│ │   ├─┬ es-to-primitive@1.1.1 
│ │   │ ├── is-date-object@1.0.1 
│ │   │ └── is-symbol@1.0.1 
│ │   ├── is-callable@1.1.3 
│ │   └── is-regex@1.0.3 
│ └── through@2.3.8 
├── tape-catch@1.0.4 
├─┬ thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
│ ├─┬ body-parser@1.15.0 
│ │ ├── bytes@2.2.0 
│ │ ├── content-type@1.0.1 
│ │ ├─┬ debug@2.2.0 
│ │ │ └── ms@0.7.1 
│ │ ├── depd@1.1.0 
│ │ ├─┬ http-errors@1.4.0 
│ │ │ └── statuses@1.2.1 
│ │ ├── iconv-lite@0.4.13 
│ │ ├─┬ on-finished@2.3.0 
│ │ │ └── ee-first@1.1.1 
│ │ ├── qs@6.1.0 
│ │ ├─┬ raw-body@2.1.6 
│ │ │ ├── bytes@2.3.0 
│ │ │ └── unpipe@1.0.0 
│ │ └─┬ type-is@1.6.12 
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
│ │ │ └── mime@1.3.4 
│ │ ├─┬ serve-static@1.10.2 
│ │ │ ├── escape-html@1.0.3 
│ │ │ └─┬ send@0.13.1 
│ │ │   ├── destroy@1.0.4 
│ │ │   └── http-errors@1.3.1 
│ │ ├── utils-merge@1.0.0 
│ │ └── vary@1.0.1 
│ ├── ip@1.1.2 
│ ├─┬ jsdoc@3.4.0
│ │ ├── escape-string-regexp@1.0.5 
│ │ └── strip-json-comments@1.0.4 
│ ├─┬ lie@3.0.2 
│ │ ├─┬ es3ify@0.1.4 
│ │ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ │ ├─┬ jstransform@3.0.0 
│ │ │ │ ├── base62@0.1.1 
│ │ │ │ └─┬ source-map@0.1.31 
│ │ │ │   └── amdefine@1.0.0 
│ │ │ └── through@2.3.8 
│ │ ├── immediate@3.0.5 
│ │ ├─┬ inline-process-browser@1.0.0 
│ │ │ ├─┬ falafel@1.2.0 
│ │ │ │ ├── acorn@1.2.2 
│ │ │ │ ├── foreach@2.0.5 
│ │ │ │ ├── isarray@0.0.1 
│ │ │ │ └── object-keys@1.0.9 
│ │ │ └─┬ through2@0.6.5 
│ │ │   └── readable-stream@1.0.33 
│ │ └─┬ unreachable-branch-transform@0.3.0 
│ │   ├── esmangle-evaluator@1.0.0 
│ │   └─┬ recast@0.10.43 
│ │     ├── ast-types@0.8.15 
│ │     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│ │     ├── private@0.1.6 
│ │     └── source-map@0.5.3 
│ ├── long@3.0.3 
│ ├─┬ multiplex@6.7.0 
│ │ ├─┬ duplexify@3.4.3 
│ │ │ ├─┬ end-of-stream@1.0.0 
│ │ │ │ └─┬ once@1.3.3 
│ │ │ │   └── wrappy@1.0.1 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── inherits@2.0.1 
│ │ ├─┬ readable-stream@2.0.6 
│ │ │ ├── core-util-is@1.0.2 
│ │ │ ├── isarray@1.0.0 
│ │ │ ├── process-nextick-args@1.0.6 
│ │ │ ├── string_decoder@0.10.31 
│ │ │ └── util-deprecate@1.0.2 
│ │ ├── varint@4.0.0 
│ │ └── xtend@4.0.1 
│ ├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ ├── node-uuid@1.4.7 
│ ├─┬ request@2.69.0 
│ │ ├── aws-sign2@0.6.0 
│ │ ├─┬ aws4@1.3.2 
│ │ │ └─┬ lru-cache@4.0.1 
│ │ │   ├── pseudomap@1.0.2 
│ │ │   └── yallist@2.0.0 
│ │ ├─┬ bl@1.0.3 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── caseless@0.11.0 
│ │ ├─┬ combined-stream@1.0.5 
│ │ │ └── delayed-stream@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├── forever-agent@0.6.1 
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
│ │ │ └─┬ pinkie-promise@2.0.0 
│ │ │   └── pinkie@2.0.4 
│ │ ├─┬ hawk@3.1.3 
│ │ │ ├── boom@2.10.1 
│ │ │ ├── cryptiles@2.0.5 
│ │ │ ├── hoek@2.16.3 
│ │ │ └── sntp@1.0.9 
│ │ ├─┬ http-signature@1.1.1 
│ │ │ ├── assert-plus@0.2.0 
│ │ │ ├─┬ jsprim@1.2.2 
│ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ ├── json-schema@0.2.2 
│ │ │ │ └── verror@1.3.6 
│ │ │ └─┬ sshpk@1.7.4 
│ │ │   ├── asn1@0.2.3 
│ │ │   └─┬ dashdash@1.13.0 
│ │ │     └── assert-plus@1.0.0 
│ │ ├── is-typedarray@1.0.0 
│ │ ├── isstream@0.1.2 
│ │ ├── json-stringify-safe@5.0.1 
│ │ ├─┬ mime-types@2.1.10 
│ │ │ └── mime-db@1.22.0 
│ │ ├── oauth-sign@0.8.1 
│ │ ├── qs@6.0.2 
│ │ ├── stringstream@0.0.5 
│ │ ├── tough-cookie@2.2.2 
│ │ └── tunnel-agent@0.4.2 
│ └── urlsafe-base64@1.0.0 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.1 
├── urlsafe-base64@1.0.0 
├── uuid@2.0.1 
└── wrapping-tape@0.0.3 


> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMultiplex.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
TAP version 13
# setup
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# calling createNativeListener directly rejects
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49776
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49778
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
DEBUG createNativeListener: listening 49781
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
DEBUG createNativeListener: listening 49785
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
DEBUG createNativeListener: listening 49790
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
DEBUG createNativeListener: listening 49794
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
DEBUG createNativeListener: listening 49798
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
DEBUG createNativeListener: listening 49802
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
DEBUG createNativeListener: listening 49806
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
DEBUG createNativeListener: listening 49858
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
DEBUG createNativeListener: listening 49862
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
DEBUG createNativeListener: listening 49865
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49866
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49867
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49869
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
ok 46 should get error
# teardown
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49871
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 47 port values should be the same
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
DEBUG createNativeListener: creating native server
ok 48 Can call startUpdateAdvertisingAndListening without error
ok 49 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49873
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
WARN createPeerListener: 
ok 50 reason should be as expected
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
DEBUG createNativeListener: creating native server
ok 51 Can call startUpdateAdvertisingAndListening without error
ok 52 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49876
DEBUG createPeerListener: pleaseConnect= false
ok 53 peerPort should not be nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
WARN createPeerListener: 
ok 54 Should not get event until connection is made
ok 55 reason should be as expected
DEBUG createPeerListener: failed incoming connection because of mux promise failure - undefined
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
DEBUG createNativeListener: creating native server
ok 56 Can call startUpdateAdvertisingAndListening without error
ok 57 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49880
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 58 Should get spontaneous connection
ok 59 peerPort != nativePort
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server
DEBUG createNativeListener: creating native server
ok 60 Can call startUpdateAdvertisingAndListening without error
ok 61 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49883
DEBUG createPeerListener: pleaseConnect= false
ok 62 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 63 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
DEBUG createNativeListener: creating native server
ok 64 Can call startUpdateAdvertisingAndListening without error
ok 65 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49887
DEBUG createPeerListener: pleaseConnect= false
ok 66 peerPort != nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 67 We should only get one connection
ok 68 buffers should be identical
# teardown
# setup
# createPeerListener is idempotent
DEBUG createNativeListener: creating native server
ok 69 Can call startUpdateAdvertisingAndListening without error
ok 70 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49891
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
ok 71 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
DEBUG createNativeListener: creating native server
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49893
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
ok 74 got our failed connection
ok 75 failed connection should reject with error
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
DEBUG createNativeListener: creating native server
ok 76 Can call startUpdateAdvertisingAndListening without error
ok 77 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49895
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
DEBUG createPeerListener: forward connection
ok 78 Should get spontaneous connection
ok 79 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === true
DEBUG createNativeListener: creating native server
ok 80 Can call startUpdateAdvertisingAndListening without error
ok 81 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49898
DEBUG createPeerListener: pleaseConnect= true
DEBUG createPeerListener: first connection
WARN createPeerListener: was expecting a forward connection to be made
ok 82 reason should be as expected
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
DEBUG createNativeListener: creating native server
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49900
DEBUG createPeerListener: pleaseConnect= false
ok 85 peerPort should not be nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  0
DEBUG createPeerListener: timed out waiting for incoming connection
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  0
DEBUG createPeerListener: no mux found
ok 86 should not get event until connection is made
ok 87 reason should be as expected
DEBUG createPeerListener: failed incoming connection because of mux promise failure - AssertionError: server._mux must exist by now
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
DEBUG createNativeListener: creating native server
ok 88 Can call startUpdateAdvertisingAndListening without error
ok 89 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49903
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  49906
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  49906
ok 90 sent and received should be the same
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
DEBUG createNativeListener: creating native server
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49907
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: looking up mux for client port:  49910
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  49910
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
ok 93 should get routerPortConnectionFailed
DEBUG createNativeListener: stream close:
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49912
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49913
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49914
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49915
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49916
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49917
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49918
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49919
# teardown
# setup
# createPeerListener - multiple parallel calls
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49920
# teardown
# setup
# closeAll can close even when connections open
ok 94 expect a specific error when the connection is closed
ok 95 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
ok 96 expect a specific error when the connection is closed
ok 97 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
ok 98 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
# teardown
# setup
# multiplex can send data
ok 99 String should be length:200
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
DEBUG createNativeListener: listening 49930
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
DEBUG createNativeListener: listening 49932
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
DEBUG createNativeListener: listening 49934
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
DEBUG createNativeListener: listening 49939
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
DEBUG createNativeListener: listening 49941
ok 158 first call should succeed
ok 159 first call should succeed
ok 160 specific error should be returned
# teardown
ok 161 error should be null
ok 162 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49943
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
DEBUG createNativeListener: listening 49948
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
DEBUG createNativeListener: listening 49950
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
DEBUG createNativeListener: listening 49955
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
DEBUG createNativeListener: listening 49957
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
ok 225 Should be able to call stopListeningForAdvertisments in teardown
ok 226 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 227 Can call startListeningForAdvertisements without error
ok 228 Can call startListeningForAdvertisements twice without error
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 229 Should be able to call stopListeningForAdvertisments in teardown
ok 230 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 231 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 232 Can call stopAdvertisingAndListening without error
# teardown
ok 233 Should be able to call stopListeningForAdvertisments in teardown
ok 234 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 235 Can call startUpdateAdvertisingAndListening without error
ok 236 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 237 Should be able to call stopListeningForAdvertisments in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 238 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 239 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 240 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49963
ok 241 no errors
ok 242 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49965
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 243 no errors
ok 244 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49967
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 245 no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 246 still no errors
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49971
ok 247 no errors
ok 248 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# can get the network status before starting
ok 249 network status should have certain non-empty properties
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# error returned with bad router
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 250 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# all services are stopped when we call stop
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49973
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
ok 251 connection to servers manager should succeed after starting
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
ok 252 connection to router server should succeed after starting
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 253 is stopped after calling stop
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 254 connection to servers manager should fail after stopping
ok 255 connection to router server should fail after stopping
# teardown
# setup
# make sure terminateConnection is properly hooked up
ok 256 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# make sure terminateListener is properly hooked up
ok 257 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# make sure we actually call kill connections properly
ok 258 IMPLEMENT ME!!!!!!
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49981
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":49980,"error":{}}
ok 259 failure reason is as expected
ok 260 error description is as expected
ok 261 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49983
ok 262 peerIdentifier matches
ok 263 error description matches
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# can do HTTP requests between peers without coordinator
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49985
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 264 found a peer! {"peerIdentifier":"foo","portNumber":49988,"hostAddress":"127.0.0.1"}
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
ok 265 Should only get expected id
DEBUG createNativeListener: stream close:
DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
ok 266 server should return 200
ok 267 response body should match testData
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: mux close
# setup
# make sure bad PSK connections fail
ok 268 FIX ME, PLEASE!!!
# teardown
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# setup
# peer changes handled from a queue
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49996
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 269 peers were handled in the right order
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50008
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 270 discovery is active
ok 271 advertising is active
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50010
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50010
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 272 right error reason
ok 273 Stop should be fine
ok 274 same port
ok 275 we should be off
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50014
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 276 discoveryActive matches
ok 277 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 278 discoveryActive matches
ok 279 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50016
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 280 discoveryActive matches
ok 281 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 282 discoveryActive matches
ok 283 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50020
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# Client to server request locally
startUpdateAdvertisingAndListening
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50021
_peerAvailabilityChanged - end
ok 284 Host address must match
ok 285 suggestedTCPTimeout must match
ok 286 connectionType must match
ok 287 portNumber must match
stopAdvertisingAndListening
# teardown
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 288 peerIdentifier should be identifier
ok 289 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 290 good beacon
ok 291 good preAmble
ok 292 public keys match!
ok 293 must return null after successful call
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 294 Response should be HTTP_BAD_RESPONSE
ok 295 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 296 Response should be NETWORK_PROBLEM
ok 297 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Test timeout locally
ok 298 Should be NETWORK_PROBLEM caused by timeout
ok 299 reject reason should be Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 300 Call start once
ok 301 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 302 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 303 Should be Killed
ok 304 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 305 Should be KILLED
ok 306 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 307 Should be KILLED
ok 308 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 309 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 310 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 311 Should be NETWORK_PROBLEM caused closing server socket
ok 312 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 313 Should be NETWORK_PROBLEM caused closing client socket
ok 314 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 315 publicKeysToNotify cannot be null
ok 316 ecdh for local device cannot be null
ok 317 milliseconds cannot be less than 0
ok 318 milliseconds cannot be 0
ok 319 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 320 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 321 should be equal
ok 322 should be equal
ok 323 (unnamed assert)
ok 324 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 325 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 326 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 327 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 328 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 329 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 330 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 331 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 332 should be equal
ok 333 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 334 should be equal
ok 335 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 336 right number of calls to address book
ok 337 good preAmble
ok 338 good unencryptedKeyId
ok 339 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 340 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 341 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 342 Matching numbers
ok 343 We have an entry!
ok 344 keys match
ok 345 secrets match
ok 346 We have an entry!
ok 347 keys match
ok 348 secrets match
ok 349 We have an entry!
ok 350 keys match
ok 351 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 352 Streams have same length
ok 353 matching size
ok 354 keys match
ok 355 secrets match
# teardown
# setup
# Add two Peers.
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:AndroidBluetooth
hostAddress:anything
portNumber:8080
_peerAvailabilityChanged - end
ok 356 should be equal
_peerAvailabilityChanged
peerIdentifier:id3212
connectionType:tcp
hostAddress:anything
portNumber:8080
_peerAvailabilityChanged - end
ok 357 should be equal
ok 358 should be equal
ok 359 should be equal
ok 360 should be equal
# teardown
killed
# setup
# TCP_NATIVE peer loses DNS
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50043
_peerAvailabilityChanged - end
ok 361 should be equal
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:undefined
portNumber:50043
_peerAvailabilityChanged - end
ok 362 should be equal
# teardown
killed
# setup
# Resolves an action locally
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50044
_peerAvailabilityChanged - end
ok 363 Host address must match
ok 364 suggestedTCPTimeout must match
ok 365 connectionType must match
ok 366 portNumber must match
# teardown
killed
# setup
# Resolves an action locally using ThaliPeerPoolDefault
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50046
_peerAvailabilityChanged - end
ok 367 Host address must match
ok 368 suggestedTCPTimeout must match
ok 369 connectionType must match
ok 370 portNumber must match
# teardown
killed
# setup
# Action fails because of a bad hostname.
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:tcp
hostAddress:address-that-does-not-exists
portNumber:123
_peerAvailabilityChanged - end
ok 371 should be equal
ok 372 should be equal
ok 373 should be equal
# teardown
killed
# setup
# hostaddress is removed when the action is running. 
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50049
_peerAvailabilityChanged - end
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:undefined
portNumber:50049
_peerAvailabilityChanged - end
ok 374 should be equal
# teardown
killed
# setup
# Start and stop ThaliNotificationServer
ok 375 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 376 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 377 StartUpdateAdvertisingAndListening should not be called
ok 378 ThaliMobile.StopAdvertisingAndListening should be called once
ok 379 no error
ok 380 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 381 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 382 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 383 no error
ok 384 should be 200
ok 385 should be equal
ok 386 should be equal
ok 387 (unnamed assert)
ok 388 no error
ok 389 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 390 error should be null
ok 391 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 392 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 393 getPeerIdentifier
ok 394 getConnectionType
ok 395 getActionType
ok 396 getActionState
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 397 initial state
ok 398 after start
ok 399 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 400 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 401 clean kill
ok 402 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 403 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 404 connection type works
ok 405 getHostAddress works
ok 406 getPortNumber works
ok 407 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 408 Entry counter must be 1
ok 409 Size must be 1
ok 410 Entry counter must be 2
ok 411 Size must be 2
ok 412 Entry2 should not be found
ok 413 Size must be 1
ok 414 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 415 Size must be100
ok 416 Entries between 20 and MAXSIZE + 20 should exist
ok 417 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 418 Entries between 6 and MAXSIZE + 4 should exist
ok 419 Size should be MAXSIZE
ok 420 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 421 WAITING state entry should not be removed
ok 422 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 423 Size should be MAXSIZE
ok 424 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 425 Kill should be called once
ok 426 Size should be 100
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 427 null arg
ok 428 wrong arg type
ok 429 wrong state
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 430 good enqueue
ok 431 should be equal
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 432 good enqueue
ok 433 2nd good enqueue
ok 434 we are in the pool
ok 435 We are out of the pool
ok 436 Action was killed
ok 437 The original kill was called too
ok 438 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 439 good enqueue
ok 440 first kill
ok 441 second NOOP kill
# teardown
# setup
# compareBufferArrays
ok 442 should throw
ok 443 should throw
ok 444 (unnamed assert)
ok 445 (unnamed assert)
ok 446 (unnamed assert)
ok 447 (unnamed assert)
ok 448 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 449 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 450 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 451 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 452 should be equal
ok 453 should be equal
ok 454 should throw
# teardown
# setup
# Test TransientState
ok 455 should throw
ok 456 should throw
ok 457 should be equal
ok 458 should be equal
ok 459 should be equal
ok 460 should be equal
ok 461 (unnamed assert)
ok 462 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 463 verify failed
ok 464 constructor called once
ok 465 constructor called with right args
ok 466 match start arg
ok 467 start called once
ok 468 stop called once
ok 469 stop after start
# teardown
# setup
# One peer and empty DB
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 470 verify failed
ok 471 constructor called once
ok 472 constructor called with right args
ok 473 match start arg
ok 474 start called once
ok 475 stop called once
ok 476 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 477 verify failed
ok 478 constructor called once
ok 479 constructor called with right args
ok 480 match start arg
ok 481 start called once
ok 482 stop called once
ok 483 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 484 verify failed
ok 485 constructor called once
ok 486 constructor called with right args
ok 487 match start arg
ok 488 start called once
ok 489 stop called once
ok 490 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 491 verify failed
ok 492 constructor called once
ok 493 constructor called with right args
ok 494 match start arg
ok 495 start called once
ok 496 stop called once
ok 497 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 498 verify failed
ok 499 constructor called once
ok 500 constructor called with right args
ok 501 match start arg
ok 502 start called once
ok 503 stop called once
ok 504 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 505 verify failed
ok 506 constructor called once
ok 507 constructor called with right args
ok 508 match start arg
ok 509 start called once
ok 510 stop called once
ok 511 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 512 verify failed
ok 513 constructor called once
ok 514 constructor called with right args
ok 515 last start before stop
ok 516 empty first start
ok 517 full second start
ok 518 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 519 verify failed
ok 520 constructor called once
ok 521 constructor called with right args
ok 522 start before stop
ok 523 We got at least 3 calls to start
ok 524 at least 3
ok 525 default 1
ok 526 1 run
ok 527 default 2
ok 528 2 run
ok 529 default 3
# teardown
# setup
# start and stop and start and stop
ok 530 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 531 back to null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 532 still null
ok 533 verify failed
ok 534 constructor called once
ok 535 constructor called with right args
ok 536 first start before first stop
ok 537 first stop before second start
ok 538 second start before second stop
# teardown
# setup
# two identical starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 539 verify failed
ok 540 constructor called once
ok 541 constructor called with right args
ok 542 (unnamed assert)
# teardown
# setup
# two different starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 543 verify failed
ok 544 constructor called once
ok 545 constructor called with right args
ok 546 (unnamed assert)
ok 547 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 548 verify failed
ok 549 constructor called once
ok 550 constructor called with right args
ok 551 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 552 verify failed
ok 553 constructor called once
ok 554 constructor called with right args
ok 555 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 556 should be equal
ok 557 should be equal
# teardown
# setup
# can create servers manager
ok 558 serversManager must not be null
ok 559 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 560 We need to call start first
# teardown
# setup
# can start/stop servers manager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50063
ok 561 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50064
ok 562 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50066
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 563 we should be connected
DEBUG createNativeListener: incoming socket close
ok 564 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50068
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50069
# teardown
# setup
ok 565 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 566 peer identifier should match
ok 567 host address should match
ok 568 port should match
ok 569 host address should be null
ok 570 port should should be null
# teardown
ok 571 should not be in started state
# setup
ok 572 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
ok 573 USN should have changed from the first one
ok 574 when receiving the second byebye, the first USN should be already set
# teardown
ok 575 should not be in started state
# setup
ok 576 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 577 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 578 should not have emitted with invalid USN
# teardown
ok 579 should not be in started state
# setup
ok 580 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 581 irrelevant messages should be ignored
ok 582 relevant messages should not be ignored
ok 583 messages from this device should be ignored
# teardown
ok 584 should not be in started state
# setup
ok 585 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 586 specific error should be returned
# teardown
ok 587 should not be in started state
# setup
ok 588 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 589 specific error should be returned
# teardown
ok 590 should not be in started state
# setup
ok 591 should be in started state
# #start should fail if called twice in a row
ok 592 specific error should be received
# teardown
ok 593 should not be in started state
# setup
ok 594 should be in started state
# should not be started after stop is called
ok 595 should not be started
ok 596 should not be listening
ok 597 should not target listening
ok 598 should not be advertising
ok 599 should not target advertising
# teardown
ok 600 should not be in started state
# setup
ok 601 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 602 specific error should be received
# teardown
ok 603 should not be in started state
# setup
ok 604 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 605 specific error expected
# teardown
ok 606 should not be in started state
# setup
ok 607 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
ok 608 server should respond with code 200
# teardown
ok 609 should not be in started state
# setup
ok 610 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
ok 611 Connection should be rejected
# teardown
ok 612 should not be in started state
# setup
ok 613 should be in started state
# #stop can be called multiple times in a row
ok 614 should be in stopped state
ok 615 should still be in stopped state
# teardown
ok 616 should not be in started state
# setup
ok 617 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 618 should be in listening state
ok 619 should still be in listening state
# teardown
ok 620 should not be in started state
# setup
ok 621 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 622 should not be in listening state
ok 623 should still not be in listening state
# teardown
ok 624 should not be in started state
# setup
ok 625 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 626 should not be in advertising state
ok 627 should still not be in advertising state
# teardown
ok 628 should not be in started state
# setup
ok 629 should be in started state
# functions are run from a queue in the right order
ok 630 call order must match
# teardown
ok 631 should not be in started state
# setup
ok 632 should be in started state
# network changes are ignored while stopping
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 633 should not be called
# teardown
ok 634 should not be in started state
# setup
ok 635 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 636 wifi should be off
ok 637 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 638 discoveryActive should be true
# teardown
ok 639 should not be in started state
# setup
ok 640 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 641 wifi should be off
ok 642 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 643 advertisingActive should be true
# teardown
ok 644 should not be in started state
# setup
ok 645 should be in started state
# when wifi is enabled discovery is activated and peers become available
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 646 wifi should be off
ok 647 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 648 peer identifier should match
ok 649 host address should match
ok 650 port should match
# teardown
ok 651 should not be in started state
# setup
# #ThaliPeerPoolDefault - single action
ok 652 is an agent
ok 653 enqueue is fine
ok 654 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 655 is an agent
ok 656 first enqueue is fine
ok 657 is an agent
ok 658 second enqueue is fine
ok 659 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 660 Queue is empty
# teardown

1..660
# tests 660
# pass  660

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
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2404V0YNdi4Rqmjo/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2404V0YNdi4Rqmjo/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2404V0YNdi4Rqmjo/TestApp/plugins/org.thaliproject.p2p/scripts
└─┬ fs-extra-promise@0.2.1 
  ├── bluebird@2.10.2 
  └─┬ fs-extra@0.24.0 
    ├── graceful-fs@4.1.3 
    ├── jsonfile@2.2.3 
    ├── path-is-absolute@1.0.0 
    └─┬ rimraf@2.5.2 
      └─┬ glob@7.0.3 
        ├─┬ inflight@1.0.4 
        │ └── wrappy@1.0.1 
        ├── inherits@2.0.1 
        ├─┬ minimatch@3.0.0 
        │ └─┬ brace-expansion@1.1.3 
        │   ├── balanced-match@0.3.0 
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
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
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
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2404V0YNdi4Rqmjo
ok 14 no error returned when creating a subfolder
# teardown
# setup
# can call hasRequiredHardware
ok 15 resolves with a boolean
# teardown
# setup
# should get right number of setup emits
Required number of ios devices presented (3)
Starting unit test run for platform: ios
Running on ios test: test-1
Required number of android devices presented (3)
Starting unit test run for platform: android
Running on android test: test-1
ok 16 received right amount of setup commands from the server
# teardown
# setup
# should discard surplus devices
Required number of ios devices presented (3)
Starting unit test run for platform: ios
Discarding surplus device: ios device 3
ok 17 should have discarded the extra device
# teardown
StopBroadcasting went ok

1..17
# tests 17
# pass  17

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-coordinated /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runCoordinatedTests.js

2016-03-29T08:08:31.490Z - info: listening on *:3000


Instance 1:
Unit Test app is loaded


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
My device name is: 784ff4e3-5efe-4d84-a7be-08490f8dde07


Instance 2:
Unit Test app is loaded


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
My device name is: 7b5fb7d3-51bf-493a-8cc8-1139e1be1979


Instance 3:
Unit Test app is loaded


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
My device name is: b8e11275-60cb-4fca-8765-68de3670459c


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMultiplex.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMultiplex.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMultiplex.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js


Instance 3:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js


2016-03-29T08:08:33.391Z - debug: Device presented: 784ff4e3-5efe-4d84-a7be-08490f8dde07 (ios) unittest socket:0


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js


2016-03-29T08:08:33.410Z - debug: Device presented: b8e11275-60cb-4fca-8765-68de3670459c (ios) unittest socket:1


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js


2016-03-29T08:08:33.466Z - debug: Device presented: 7b5fb7d3-51bf-493a-8cc8-1139e1be1979 (ios) unittest socket:2


2016-03-29T08:08:33.466Z - info: Required number of ios devices presented (3)


2016-03-29T08:08:33.467Z - info: Starting unit test run for platform: ios


Instance 1:
TAP version 13


Instance 1:
# setup


Instance 2:
TAP version 13


Instance 2:
# setup


Instance 3:
TAP version 13


2016-03-29T08:08:33.605Z - info: Running on ios test: 1. calling createNativeListener directly rejects


Instance 3:
# setup


Instance 1:
# 1. calling createNativeListener directly rejects


Instance 2:
# 1. calling createNativeListener directly rejects


Instance 3:
# 1. calling createNativeListener directly rejects


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50112


Instance 1:
ok 1 Should throw


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: listening 50113


Instance 2:
ok 1 Should throw


Instance 2:
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50114


Instance 3:
ok 1 Should throw


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:33.643Z - info: Running on ios test: 2. emits incomingConnectionState


Instance 1:
# 2. emits incomingConnectionState


Instance 2:
# 2. emits incomingConnectionState


Instance 3:
# 2. emits incomingConnectionState


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50118


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50120


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 1:
ok 2 initial connection state should be CONNECTED


Instance 2:
DEBUG createNativeListener: new mux


Instance 2:
ok 2 initial connection state should be CONNECTED


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
ok 3 final connection state should be DISCONNECTED


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50122


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 3 final connection state should be DISCONNECTED


Instance 2:
# teardown


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
ok 2 initial connection state should be CONNECTED


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
ok 3 final connection state should be DISCONNECTED


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:33.685Z - info: Running on ios test: 3. emits routerPortConnectionFailed


Instance 1:
# 3. emits routerPortConnectionFailed


Instance 2:
# 3. emits routerPortConnectionFailed


Instance 3:
# 3. emits routerPortConnectionFailed


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50127


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: listening 50129


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50132


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 


Instance 2:
ok 4 tried to connect to right port


Instance 2:
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted


Instance 2:
# teardown
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: 


Instance 3:
ok 4 tried to connect to right port


Instance 3:
ok 5 failed due to refused connection


Instance 3:
ok 6 routerPortConnectionFailed is emitted


Instance 3:
# teardown


Instance 3:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
# setup
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: mux close
# setup


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
# setup
DEBUG createNativeListener: incoming socket close


2016-03-29T08:08:33.730Z - info: Running on ios test: 4. native server connections all up


Instance 1:
# 4. native server connections all up


Instance 2:
# 4. native server connections all up


Instance 3:
# 4. native server connections all up


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50139


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: listening 50141


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50143
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
ok 7 Send/recvd #1 should be equal length


Instance 2:
ok 8 Send/recvd #1 should be same


Instance 2:
ok 9 Send/recvd #2 should be equal length


Instance 2:
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets


Instance 2:
# teardown


Instance 3:
ok 7 Send/recvd #1 should be equal length


Instance 3:
ok 8 Send/recvd #1 should be same


Instance 3:
ok 9 Send/recvd #2 should be equal length


Instance 3:
ok 10 Send/recvd #2 should be same


Instance 3:
ok 11 Should be exactly 2 client sockets


Instance 3:
# teardown


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: mux close
# setup


Instance 2:
# setup


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
# setup


Instance 3:
DEBUG createNativeListener: incoming socket close


2016-03-29T08:08:33.785Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket


Instance 1:
# 5. native server - closing incoming stream cleans outgoing socket


Instance 2:
# 5. native server - closing incoming stream cleans outgoing socket


Instance 3:
# 5. native server - closing incoming stream cleans outgoing socket


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50154


Instance 3:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50156


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: listening 50158


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open


Instance 2:
# teardown


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
ok 12 socket shouldn't close until after stream


Instance 3:
ok 13 incoming remains open


Instance 3:
# teardown


Instance 1:
DEBUG createNativeListener: mux close
# setup


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
# setup
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
# setup


Instance 3:
DEBUG createNativeListener: incoming socket close


2016-03-29T08:08:33.822Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket


Instance 1:
# 6. native server - closing incoming connection cleans outgoing socket


Instance 2:
# 6. native server - closing incoming connection cleans outgoing socket


Instance 3:
# 6. native server - closing incoming connection cleans outgoing socket


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50166


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: listening 50168


Instance 1:
ok 14 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up


Instance 2:
ok 14 we should not have gotten an error


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: listening 50172


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up


Instance 2:
# teardown


Instance 3:
ok 14 we should not have gotten an error


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
ok 15 socket shouldn't close until after incoming


Instance 3:
ok 16 incoming is cleaned up


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:33.852Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream


Instance 1:
# 7. native server - closing outgoing socket cleans associated mux stream


Instance 2:
# 7. native server - closing outgoing socket cleans associated mux stream


Instance 3:
# 7. native server - closing outgoing socket cleans associated mux stream


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50178


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50180


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50184


Instance 2:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
ok 17 stream was closed
ok 18 incoming should survive


Instance 2:
ok 19 mux should have no streams


Instance 2:
# teardown


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
ok 17 stream was closed


Instance 3:
ok 18 incoming should survive


Instance 3:
ok 19 mux should have no streams


Instance 3:
# teardown


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
# setup


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
# setup


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
# setup


Instance 3:
DEBUG createNativeListener: incoming socket close


2016-03-29T08:08:33.889Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up


Instance 1:
# 8. native server - closing the whole server cleans everything up


Instance 2:
# 8. native server - closing the whole server cleans everything up


Instance 3:
# 8. native server - closing the whole server cleans everything up


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50190


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: listening 50192


Instance 1:
DEBUG createNativeListener: new mux


Instance 1:
ok 20 we should not have gotten an error
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 1:
ok 21 Buffers are identical


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done


Instance 3:
DEBUG createNativeListener: listening 50195


Instance 1:
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 20 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 2:
ok 21 Buffers are identical


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 2:
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close


Instance 2:
# teardown


Instance 3:
ok 20 we should not have gotten an error


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
ok 21 Buffers are identical


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
ok 22 native server is nulled out
ok 23 native server should be closed


Instance 3:
ok 24 incoming has been removed


Instance 3:
ok 25 Incoming should be done
ok 26 The mux object should be closed


Instance 3:
ok 27 The mux stream should be closed


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:33.932Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely


Instance 1:
# 9. native server - we can get a ton of connections and data through and still clean up the server completely


Instance 2:
# 9. native server - we can get a ton of connections and data through and still clean up the server completely


Instance 3:
# 9. native server - we can get a ton of connections and data through and still clean up the server completely


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50202


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50203


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
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


Instance 1:
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


Instance 3:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: listening 50245


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 3:
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


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 2:
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


Instance 1:
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


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 3:
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


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 3:
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


Instance 2:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close


Instance 1:
ok 28 native server is nulled out


Instance 1:
ok 29 native server should be closed


Instance 1:
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 28 native server is nulled out


Instance 2:
ok 29 native server should be closed


Instance 2:
ok 30 incoming has been removed


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
# teardown


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
ok 28 native server is nulled out


Instance 3:
ok 29 native server should be closed


Instance 3:
ok 30 incoming has been removed


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# teardown


Instance 3:
# setup


2016-03-29T08:08:35.175Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up


Instance 1:
# 10. native server - simulate mux failure, make sure everything is cleaned up


Instance 3:
# 10. native server - simulate mux failure, make sure everything is cleaned up


Instance 2:
# 10. native server - simulate mux failure, make sure everything is cleaned up


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50362


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50358
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50359


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
ok 31 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 31 we should not have gotten an error


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
ok 32 Buffers are identical


Instance 1:
ok 32 Buffers are identical


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 33 server should be fine


Instance 1:
ok 33 server should be fine


Instance 1:
ok 34 server should be open


Instance 1:
ok 35 incoming has been removed


Instance 2:
ok 34 server should be open


Instance 2:
ok 35 incoming has been removed


Instance 1:
ok 36 The mux object should be closed


Instance 2:
ok 36 The mux object should be closed


Instance 2:
ok 37 The mux stream should be closed


Instance 1:
ok 37 The mux stream should be closed


Instance 2:
# teardown


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
ok 31 we should not have gotten an error


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
ok 32 Buffers are identical


Instance 3:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
ok 33 server should be fine


Instance 3:
ok 34 server should be open


Instance 3:
ok 35 incoming has been removed


Instance 3:
ok 36 The mux object should be closed


Instance 3:
ok 37 The mux stream should be closed


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.220Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up


Instance 1:
# 11. native server - timing out the incoming connection cleans everything up


Instance 3:
# 11. native server - timing out the incoming connection cleans everything up


Instance 2:
# 11. native server - timing out the incoming connection cleans everything up


Instance 3:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50370


Instance 3:
DEBUG createNativeListener: listening 50371


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 1:
ok 38 we should not have gotten an error


Instance 3:
ok 38 we should not have gotten an error


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
ok 39 Buffers are identical


Instance 1:
ok 39 Buffers are identical


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50376


Instance 1:
DEBUG createNativeListener: incoming socket timeout


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 2:
ok 38 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: mux close


Instance 2:
ok 39 Buffers are identical


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
ok 40 server should be fine


Instance 1:
ok 41 server should be open


Instance 1:
ok 42 incoming has been removed


Instance 1:
ok 43 The mux object should be closed


Instance 1:
ok 44 The mux stream should be closed


Instance 3:
DEBUG createNativeListener: incoming socket timeout


Instance 3:
DEBUG createNativeListener: stream close:


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: incoming socket timeout


Instance 2:
DEBUG createNativeListener: stream close:


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
ok 40 server should be fine


Instance 3:
ok 41 server should be open


Instance 3:
ok 42 incoming has been removed


Instance 3:
ok 43 The mux object should be closed


Instance 3:
ok 44 The mux stream should be closed


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 40 server should be fine


Instance 2:
ok 41 server should be open


Instance 3:
# teardown


Instance 2:
ok 42 incoming has been removed


Instance 2:
ok 43 The mux object should be closed


Instance 2:
ok 44 The mux stream should be closed


Instance 2:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.264Z - info: Running on ios test: 12. closeAll can close even when connections open


Instance 1:
# 12. closeAll can close even when connections open


Instance 3:
# 12. closeAll can close even when connections open


Instance 2:
# 12. closeAll can close even when connections open


Instance 1:
ok 45 not possible to connect to the server anymore


Instance 1:
# teardown


Instance 2:
ok 45 expect a specific error when the connection is closed


Instance 2:
ok 46 not possible to connect to the server anymore


Instance 3:
ok 45 not possible to connect to the server anymore


Instance 2:
# teardown


Instance 3:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.284Z - info: Running on ios test: 13. closeAll with promise


Instance 1:
# 13. closeAll with promise


Instance 2:
# 13. closeAll with promise


Instance 3:
# 13. closeAll with promise


Instance 3:
ok 46 not possible to connect to the server anymore


Instance 3:
# teardown


Instance 1:
ok 46 not possible to connect to the server anymore


Instance 1:
# teardown


Instance 2:
ok 47 not possible to connect to the server anymore


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.308Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false


Instance 2:
# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false


Instance 3:
# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false


Instance 1:
# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false


Instance 1:
ok 47 Got the right error


Instance 1:
# teardown


Instance 3:
ok 47 Got the right error
# teardown


Instance 2:
ok 48 Got the right error


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.329Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true


Instance 1:
# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true


Instance 3:
# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true


Instance 2:
# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:35.347Z - info: Running on ios test: 16. multiplex can send data


Instance 1:
# 16. multiplex can send data


Instance 3:
# 16. multiplex can send data


Instance 2:
# 16. multiplex can send data


Instance 3:
ok 48 String should be length:200


Instance 2:
ok 49 String should be length:200


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
ok 48 String should be length:200


Instance 1:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.371Z - info: Running on ios test: 17. enqueue and run in order


Instance 3:
# 17. enqueue and run in order


Instance 1:
# 17. enqueue and run in order


Instance 2:
# 17. enqueue and run in order


Instance 3:
ok 49 firstPromise setTimeout
ok 50 firstPromise result
ok 51 firstPromise testValue


Instance 1:
ok 49 firstPromise setTimeout
ok 50 firstPromise result
ok 51 firstPromise testValue


Instance 2:
ok 50 firstPromise setTimeout


Instance 2:
ok 51 firstPromise result


Instance 2:
ok 52 firstPromise testValue


Instance 1:
ok 52 secondPromise setTimeout


Instance 3:
ok 52 secondPromise setTimeout


Instance 1:
ok 53 secondPromise result


Instance 1:
ok 54 secondPromise testValue


Instance 3:
ok 53 secondPromise result


Instance 3:
ok 54 secondPromise testValue


Instance 1:
ok 55 thirdPromise in promise


Instance 3:
ok 55 thirdPromise in promise


Instance 1:
ok 56 thirdPromise result


Instance 3:
ok 56 thirdPromise result


Instance 1:
ok 57 thirdPromise testValue


Instance 3:
ok 57 thirdPromise testValue


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
ok 53 secondPromise setTimeout


Instance 2:
ok 54 secondPromise result


Instance 2:
ok 55 secondPromise testValue


Instance 2:
ok 56 thirdPromise in promise


Instance 2:
ok 57 thirdPromise result


Instance 2:
ok 58 thirdPromise testValue


Instance 2:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:35.621Z - info: Running on ios test: 18. enqueueAtTop and run backwards


Instance 1:
# 18. enqueueAtTop and run backwards


Instance 3:
# 18. enqueueAtTop and run backwards


Instance 2:
# 18. enqueueAtTop and run backwards


Instance 3:
ok 58 thirdPromise - first to run


Instance 1:
ok 58 thirdPromise - first to run


Instance 3:
ok 59 thirdPromise - in resolve


Instance 3:
ok 60 secondPromise - second to run


Instance 1:
ok 59 thirdPromise - in resolve


Instance 3:
ok 61 secondPromise - in catch


Instance 1:
ok 60 secondPromise - second to run


Instance 3:
ok 62 firstPromise - third to run


Instance 1:
ok 61 secondPromise - in catch


Instance 1:
ok 62 firstPromise - third to run


Instance 3:
ok 63 firstPromise - in then


Instance 1:
ok 63 firstPromise - in then


Instance 1:
ok 64 testing promises


Instance 3:
ok 64 testing promises


Instance 3:
# teardown


Instance 1:
# teardown


Instance 2:
ok 59 thirdPromise - first to run


Instance 2:
ok 60 thirdPromise - in resolve


Instance 2:
ok 61 secondPromise - second to run


Instance 2:
ok 62 secondPromise - in catch


Instance 2:
ok 63 firstPromise - third to run


Instance 2:
ok 64 firstPromise - in then


Instance 2:
ok 65 testing promises


Instance 2:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:35.645Z - info: Running on ios test: 19. mix enqueue and enqueueAtTop


Instance 2:
# 19. mix enqueue and enqueueAtTop


Instance 1:
# 19. mix enqueue and enqueueAtTop


Instance 3:
# 19. mix enqueue and enqueueAtTop


Instance 2:
ok 66 fourth


Instance 2:
ok 67 fourth


Instance 2:
ok 68 second


Instance 2:
ok 69 secondPromise - in then


Instance 1:
ok 65 fourth


Instance 1:
ok 66 fourth


Instance 1:
ok 67 second


Instance 1:
ok 68 secondPromise - in then


Instance 3:
ok 65 fourth


Instance 3:
ok 66 fourth


Instance 3:
ok 67 second


Instance 3:
ok 68 secondPromise - in then


Instance 2:
ok 70 first
ok 71 firstPromise - in catch
ok 72 third
ok 73 thirdPromise - in then
ok 74 testingPromises


Instance 1:
ok 69 first
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises


Instance 2:
# teardown


Instance 1:
# teardown


Instance 3:
ok 69 first


Instance 3:
ok 70 firstPromise - in catch


Instance 3:
ok 71 third


Instance 3:
ok 72 thirdPromise - in then
ok 73 testingPromises


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:35.772Z - info: Running on ios test: 20. queues handled independently


Instance 1:
# 20. queues handled independently


Instance 3:
# 20. queues handled independently


Instance 2:
# 20. queues handled independently


Instance 1:
ok 74 all short operations completed before the long resolves
# teardown


Instance 2:
ok 75 all short operations completed before the long resolves
# teardown


Instance 3:
ok 74 all short operations completed before the long resolves
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:35.834Z - info: Running on ios test: 21. basic


Instance 1:
# 21. basic


Instance 3:
# 21. basic


Instance 2:
# 21. basic


Instance 3:
ok 75 sane
# teardown


Instance 1:
ok 75 sane


Instance 1:
# teardown


Instance 2:
ok 76 sane


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.856Z - info: Running on ios test: 22. another


Instance 1:
# 22. another


Instance 3:
# 22. another


Instance 2:
# 22. another


Instance 1:
ok 76 sane
# teardown


Instance 3:
ok 76 sane


Instance 2:
ok 77 sane


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:35.884Z - info: Running on ios test: 23. can pass data in setup


Instance 1:
# 23. can pass data in setup


Instance 3:
# 23. can pass data in setup


Instance 2:
# 23. can pass data in setup


Instance 1:
ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
# teardown


Instance 3:
ok 77 test participant has uuid
ok 78 participant data matches


Instance 3:
ok 79 test participant has uuid


Instance 3:
ok 80 participant data matches
ok 81 test participant has uuid


Instance 3:
ok 82 participant data matches


Instance 3:
# teardown


Instance 2:
ok 78 test participant has uuid


Instance 2:
ok 79 participant data matches


Instance 2:
ok 80 test participant has uuid


Instance 2:
ok 81 participant data matches


Instance 2:
ok 82 test participant has uuid


Instance 2:
ok 83 participant data matches


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:35.905Z - info: Running on ios test: 24. #startListeningForAdvertisements should fail if start not called


Instance 1:
# 24. #startListeningForAdvertisements should fail if start not called


Instance 3:
# 24. #startListeningForAdvertisements should fail if start not called


Instance 2:
# 24. #startListeningForAdvertisements should fail if start not called


Instance 1:
ok 83 specific error should be returned
# teardown


Instance 2:
ok 84 specific error should be returned
# teardown


Instance 3:
ok 83 specific error should be returned


Instance 3:
# teardown


Instance 1:
ok 84 error should be null
ok 85 error should be null
# setup


Instance 3:
ok 84 error should be null


Instance 3:
ok 85 error should be null
# setup


Instance 2:
ok 85 error should be null


Instance 2:
ok 86 error should be null


Instance 2:
# setup


2016-03-29T08:08:35.927Z - info: Running on ios test: 25. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
# 25. #startUpdateAdvertisingAndListening should fail if start not called


Instance 3:
# 25. #startUpdateAdvertisingAndListening should fail if start not called


Instance 2:
# 25. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
ok 86 specific error should be returned


Instance 1:
# teardown


Instance 2:
ok 87 specific error should be returned
# teardown


Instance 3:
ok 86 specific error should be returned


Instance 3:
# teardown


Instance 3:
ok 87 error should be null
ok 88 error should be null
# setup


Instance 1:
ok 87 error should be null
ok 88 error should be null


Instance 1:
# setup


Instance 2:
ok 88 error should be null


Instance 2:
ok 89 error should be null


Instance 2:
# setup


2016-03-29T08:08:35.948Z - info: Running on ios test: 26. should be able to call #stopListeningForAdvertisements many times


Instance 1:
# 26. should be able to call #stopListeningForAdvertisements many times


Instance 2:
# 26. should be able to call #stopListeningForAdvertisements many times


Instance 3:
# 26. should be able to call #stopListeningForAdvertisements many times


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50404


Instance 1:
ok 89 error should be null
ok 90 error should be null


Instance 1:
ok 91 error should be null


Instance 1:
ok 92 error should be null


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50407
ok 90 error should be null
ok 91 error should be null
ok 92 error should be null
ok 93 error should be null
# teardown


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50408


Instance 3:
ok 89 error should be null


Instance 3:
ok 90 error should be null


Instance 3:
ok 91 error should be null


Instance 3:
ok 92 error should be null


Instance 3:
# teardown


Instance 2:
ok 94 error should be null
ok 95 error should be null
# setup


Instance 3:
ok 93 error should be null


Instance 3:
ok 94 error should be null
# setup


Instance 1:
ok 93 error should be null


Instance 1:
ok 94 error should be null


Instance 1:
# setup


2016-03-29T08:08:35.998Z - info: Running on ios test: 27. should be able to call #startListeningForAdvertisements many times


Instance 3:
# 27. should be able to call #startListeningForAdvertisements many times


Instance 2:
# 27. should be able to call #startListeningForAdvertisements many times


Instance 1:
# 27. should be able to call #startListeningForAdvertisements many times


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50410
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 96 error should be null
ok 97 error should be null
ok 98 error should be null
ok 99 error should be null
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50412


Instance 1:
DEBUG createNativeListener: listening 50414


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 95 error should be null
ok 96 error should be null
ok 97 error should be null
ok 98 error should be null
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
ok 95 error should be null


Instance 1:
ok 96 error should be null


Instance 1:
ok 97 error should be null


Instance 1:
ok 98 error should be null


Instance 1:
# teardown


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 100 error should be null
ok 101 error should be null
# setup


Instance 3:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
ok 99 error should be null


Instance 3:
ok 100 error should be null


Instance 1:
ok 99 error should be null


Instance 3:
# setup


Instance 1:
ok 100 error should be null


Instance 1:
# setup


2016-03-29T08:08:36.028Z - info: Running on ios test: 28. should be able to call #startUpdateAdvertisingAndListening many times


Instance 3:
# 28. should be able to call #startUpdateAdvertisingAndListening many times


Instance 2:
# 28. should be able to call #startUpdateAdvertisingAndListening many times


Instance 1:
# 28. should be able to call #startUpdateAdvertisingAndListening many times


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50416
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 102 error should be null
ok 103 error should be null


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50418


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50422


Instance 2:
ok 104 error should be null
ok 105 error should be null


Instance 2:
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 101 error should be null


Instance 3:
ok 102 error should be null


Instance 3:
ok 103 error should be null
ok 104 error should be null


Instance 3:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
ok 101 error should be null


Instance 1:
ok 102 error should be null


Instance 1:
ok 103 error should be null


Instance 1:
ok 104 error should be null


Instance 1:
# teardown


Instance 3:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 106 error should be null
ok 107 error should be null
# setup


Instance 3:
ok 105 error should be null
ok 106 error should be null


Instance 3:
# setup


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 105 error should be null


Instance 1:
ok 106 error should be null


Instance 1:
# setup


2016-03-29T08:08:36.073Z - info: Running on ios test: 29. should be able to call #stopAdvertisingAndListening many times


Instance 2:
# 29. should be able to call #stopAdvertisingAndListening many times


Instance 3:
# 29. should be able to call #stopAdvertisingAndListening many times


Instance 1:
# 29. should be able to call #stopAdvertisingAndListening many times


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50431


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50433
ok 107 error should be null
ok 108 error should be null


Instance 2:
ok 108 error should be null
ok 109 error should be null
ok 110 error should be null


Instance 3:
ok 109 error should be null


Instance 2:
ok 111 error should be null
# teardown


Instance 3:
ok 110 error should be null
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50435


Instance 1:
ok 107 error should be null


Instance 1:
ok 108 error should be null


Instance 1:
ok 109 error should be null


Instance 1:
ok 110 error should be null


Instance 1:
# teardown


Instance 3:
ok 111 error should be null


Instance 2:
ok 112 error should be null
ok 113 error should be null
# setup


Instance 3:
ok 112 error should be null
# setup


Instance 1:
ok 111 error should be null


Instance 1:
ok 112 error should be null


Instance 1:
# setup


2016-03-29T08:08:36.100Z - info: Running on ios test: 30. #start should fail if called twice in a row


Instance 1:
# 30. #start should fail if called twice in a row


Instance 3:
# 30. #start should fail if called twice in a row


Instance 2:
# 30. #start should fail if called twice in a row


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50437
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50439
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned


Instance 3:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50441


Instance 2:
ok 114 first call should succeed


Instance 2:
ok 115 first call should succeed


Instance 2:
ok 116 specific error should be returned


Instance 2:
# teardown


Instance 1:
ok 116 error should be null
ok 117 error should be null
# setup


Instance 3:
ok 116 error should be null
ok 117 error should be null
# setup


Instance 2:
ok 117 error should be null


Instance 2:
ok 118 error should be null


Instance 2:
# setup


2016-03-29T08:08:36.122Z - info: Running on ios test: 31. does not emit duplicate discoveryAdvertisingStateUpdate


Instance 3:
# 31. does not emit duplicate discoveryAdvertisingStateUpdate


Instance 1:
# 31. does not emit duplicate discoveryAdvertisingStateUpdate


Instance 2:
# 31. does not emit duplicate discoveryAdvertisingStateUpdate


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50444
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50445
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50453


Instance 3:
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
# teardown


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 121 error should be null
ok 122 error should be null


Instance 1:
# setup


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 3:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 121 error should be null
ok 122 error should be null


Instance 3:
# setup


Instance 2:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 122 error should be null


Instance 2:
ok 123 error should be null


Instance 2:
# setup


2016-03-29T08:08:36.176Z - info: Running on ios test: 32. does not send duplicate availability changes


Instance 1:
# 32. does not send duplicate availability changes


Instance 3:
# 32. does not send duplicate availability changes


Instance 2:
# 32. does not send duplicate availability changes


Instance 1:
ok 123 should be called once
ok 124 should not have been called more than once
# teardown


Instance 3:
ok 123 should be called once
ok 124 should not have been called more than once


Instance 2:
ok 124 should be called once


Instance 3:
# teardown


Instance 2:
ok 125 should not have been called more than once


Instance 2:
# teardown


Instance 1:
ok 125 error should be null
ok 126 error should be null


Instance 3:
ok 125 error should be null
ok 126 error should be null
# setup


Instance 1:
# setup


Instance 2:
ok 126 error should be null


Instance 2:
ok 127 error should be null


Instance 2:
# setup


2016-03-29T08:08:36.202Z - info: Running on ios test: 33. can get the network status


Instance 1:
# 33. can get the network status


Instance 2:
# 33. can get the network status


Instance 3:
# 33. can get the network status


Instance 1:
ok 127 network status should have certain non-empty properties
# teardown


Instance 3:
ok 127 network status should have certain non-empty properties


Instance 3:
# teardown


Instance 2:
ok 128 network status should have certain non-empty properties


Instance 2:
# teardown


Instance 1:
ok 128 error should be null
ok 129 error should be null
# setup


Instance 3:
ok 128 error should be null
ok 129 error should be null


Instance 3:
# setup


Instance 2:
ok 129 error should be null


Instance 2:
ok 130 error should be null


Instance 2:
# setup


2016-03-29T08:08:36.218Z - info: Running on ios test: 34. wifi peer is marked unavailable if announcements stop


Instance 1:
# 34. wifi peer is marked unavailable if announcements stop


Instance 2:
# 34. wifi peer is marked unavailable if announcements stop


Instance 3:
# 34. wifi peer is marked unavailable if announcements stop


Instance 1:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined


Instance 3:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined


Instance 1:
ok 130 host address should match
ok 131 port should match


Instance 2:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined


Instance 3:
ok 130 host address should match
ok 131 port should match


Instance 2:
ok 131 host address should match


Instance 2:
ok 132 port should match


Instance 2:
ok 133 host address should be null


Instance 2:
ok 134 port should should be null


Instance 2:
# teardown


Instance 1:
ok 132 host address should be null
ok 133 port should should be null


Instance 3:
ok 132 host address should be null
ok 133 port should should be null


Instance 3:
# teardown


Instance 1:
# teardown


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
ok 135 error should be null
ok 136 error should be null
# setup


Instance 3:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null


Instance 3:
# setup


2016-03-29T08:08:38.253Z - info: Running on ios test: 35. network changes emitted correctly


Instance 3:
# 35. network changes emitted correctly


Instance 1:
# 35. network changes emitted correctly


Instance 2:
# 35. network changes emitted correctly


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50462
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 136 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 137 wifi is on
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50463
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 137 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 138 wifi is on
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50465


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
ok 136 wifi is off


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
ok 137 wifi is on


Instance 3:
# teardown


Instance 1:
ok 138 error should be null
ok 139 error should be null
# setup


Instance 2:
ok 139 error should be null
ok 140 error should be null
# setup


Instance 3:
ok 138 error should be null
ok 139 error should be null
# setup


2016-03-29T08:08:38.281Z - info: Running on ios test: 36. network changes not emitted in stopped state


Instance 1:
# 36. network changes not emitted in stopped state


Instance 3:
# 36. network changes not emitted in stopped state


Instance 2:
# 36. network changes not emitted in stopped state


Instance 1:
ok 140 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown


Instance 2:
ok 141 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown


Instance 3:
ok 140 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
# teardown


Instance 1:
ok 141 error should be null
ok 142 error should be null
# setup


Instance 2:
ok 142 error should be null
ok 143 error should be null
# setup


Instance 3:
ok 141 error should be null
ok 142 error should be null
# setup


2016-03-29T08:08:38.297Z - info: Running on ios test: 37. calls correct starts when network changes


Instance 1:
# 37. calls correct starts when network changes


Instance 2:
# 37. calls correct starts when network changes


Instance 3:
# 37. calls correct starts when network changes


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50468
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 144 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 145 specific error expected


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50469
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 143 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 144 specific error expected
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50476
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 143 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 144 specific error expected


Instance 2:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}


Instance 3:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
ok 145 startListeningForAdvertisements should have been called
ok 146 startUpdateAdvertisingAndListening should have been called
# teardown


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}


Instance 2:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 146 startListeningForAdvertisements should have been called
ok 147 startUpdateAdvertisingAndListening should have been called


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
# teardown


Instance 1:
ok 145 startListeningForAdvertisements should have been called
ok 146 startUpdateAdvertisingAndListening should have been called


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
# teardown


Instance 3:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 147 error should be null
ok 148 error should be null


Instance 1:
# setup


Instance 3:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
ok 147 error should be null
ok 148 error should be null
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 148 error should be null


Instance 2:
ok 149 error should be null


Instance 2:
# setup


2016-03-29T08:08:38.355Z - info: Running on ios test: 38. peer is marked unavailable if port number changes


Instance 1:
# 38. peer is marked unavailable if port number changes


Instance 2:
# 38. peer is marked unavailable if port number changes


Instance 3:
# 38. peer is marked unavailable if port number changes


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50493
ok 149 peer should have a non-empty identifier
ok 150 peer should have a non-empty host address
ok 151 peer should have port number
ok 152 peer should have suggested timeout
ok 153 peer should have a connection type
ok 154 connection type should match one of the pre-defined types
ok 155 peer should have a non-empty identifier
ok 156 host address should be null
ok 157 port number should be null
ok 158 peer should have suggested timeout
ok 159 peer should have a connection type
ok 160 connection type should match one of the pre-defined types
ok 161 port number must match
ok 162 peer should have a non-empty identifier
ok 163 peer should have a non-empty host address
ok 164 peer should have port number
ok 165 peer should have suggested timeout
ok 166 peer should have a connection type
ok 167 connection type should match one of the pre-defined types
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50494
ok 150 peer should have a non-empty identifier
ok 151 peer should have a non-empty host address
ok 152 peer should have port number
ok 153 peer should have suggested timeout
ok 154 peer should have a connection type
ok 155 connection type should match one of the pre-defined types
ok 156 peer should have a non-empty identifier
ok 157 host address should be null
ok 158 port number should be null
ok 159 peer should have suggested timeout
ok 160 peer should have a connection type
ok 161 connection type should match one of the pre-defined types
ok 162 port number must match
ok 163 peer should have a non-empty identifier
ok 164 peer should have a non-empty host address
ok 165 peer should have port number
ok 166 peer should have suggested timeout
ok 167 peer should have a connection type
ok 168 connection type should match one of the pre-defined types
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50496


Instance 3:
ok 149 peer should have a non-empty identifier


Instance 3:
ok 150 peer should have a non-empty host address


Instance 3:
ok 151 peer should have port number


Instance 3:
ok 152 peer should have suggested timeout


Instance 3:
ok 153 peer should have a connection type
ok 154 connection type should match one of the pre-defined types


Instance 3:
ok 155 peer should have a non-empty identifier


Instance 3:
ok 156 host address should be null


Instance 3:
ok 157 port number should be null


Instance 3:
ok 158 peer should have suggested timeout


Instance 3:
ok 159 peer should have a connection type


Instance 3:
ok 160 connection type should match one of the pre-defined types


Instance 3:
ok 161 port number must match


Instance 3:
ok 162 peer should have a non-empty identifier


Instance 3:
ok 163 peer should have a non-empty host address


Instance 3:
ok 164 peer should have port number


Instance 3:
ok 165 peer should have suggested timeout


Instance 3:
ok 166 peer should have a connection type
ok 167 connection type should match one of the pre-defined types


Instance 3:
# teardown


Instance 1:
ok 168 error should be null
ok 169 error should be null


Instance 1:
# setup


Instance 3:
ok 168 error should be null
ok 169 error should be null


Instance 3:
# setup


Instance 2:
ok 169 error should be null
ok 170 error should be null


Instance 2:
# setup


2016-03-29T08:08:38.386Z - info: Running on ios test: 39. when network connection is lost a peer should be marked unavailable


Instance 1:
# 39. when network connection is lost a peer should be marked unavailable


Instance 3:
# 39. when network connection is lost a peer should be marked unavailable


Instance 2:
# 39. when network connection is lost a peer should be marked unavailable


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50498


Instance 1:
INFO testUtils: Toggling radios to: false


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50500
INFO testUtils: Toggling radios to: false


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
ok 170 peer should have a non-empty identifier
ok 171 host address should be null
ok 172 port number should be null
ok 173 peer should have suggested timeout
ok 174 peer should have a connection type
ok 175 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true


Instance 3:
ok 170 peer should have a non-empty identifier
ok 171 host address should be null
ok 172 port number should be null
ok 173 peer should have suggested timeout
ok 174 peer should have a connection type
ok 175 connection type should match one of the pre-defined types
INFO testUtils: Toggling radios to: true


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50502


Instance 2:
INFO testUtils: Toggling radios to: false


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 171 peer should have a non-empty identifier


Instance 2:
ok 172 host address should be null


Instance 2:
ok 173 port number should be null


Instance 2:
ok 174 peer should have suggested timeout


Instance 2:
ok 175 peer should have a connection type


Instance 2:
ok 176 connection type should match one of the pre-defined types


Instance 2:
INFO testUtils: Toggling radios to: true


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
ok 176 error should be null
ok 177 error should be null


Instance 3:
ok 176 error should be null
ok 177 error should be null
# setup


Instance 1:
# setup


Instance 2:
ok 177 error should be null


Instance 2:
ok 178 error should be null
# setup


2016-03-29T08:08:38.421Z - info: Running on ios test: 40. peer should be found once after listening and discovery started


Instance 1:
# 40. peer should be found once after listening and discovery started


Instance 3:
# 40. peer should be found once after listening and discovery started


Instance 2:
# 40. peer should be found once after listening and discovery started


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50505
ok 178 error should be null
ok 179 error should be null


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50506
ok 178 error should be null
ok 179 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 180 error should be null
ok 181 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 error should be null
ok 183 error should be null


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50511
ok 179 error should be null
ok 180 error should be null


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 180 error should be null
ok 181 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 182 error should be null
ok 183 error should be null


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 181 error should be null
ok 182 error should be null
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 183 error should be null


Instance 2:
ok 184 error should be null


Instance 1:
ok 184 peer should have a non-empty identifier


Instance 1:
ok 185 peer should have a non-empty host address


Instance 1:
ok 186 peer should have port number


Instance 1:
ok 187 peer should have suggested timeout


Instance 1:
ok 188 peer should have a connection type


Instance 1:
ok 189 connection type should match one of the pre-defined types


Instance 3:
ok 184 peer should have a non-empty identifier
ok 185 peer should have a non-empty host address
ok 186 peer should have port number
ok 187 peer should have suggested timeout
ok 188 peer should have a connection type
ok 189 connection type should match one of the pre-defined types
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 185 peer should have a non-empty identifier
ok 186 peer should have a non-empty host address
ok 187 peer should have port number
ok 188 peer should have suggested timeout
ok 189 peer should have a connection type
ok 190 connection type should match one of the pre-defined types


Instance 3:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 1:
not ok 190 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:501:9)
  ...


Instance 3:
not ok 190 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:501:9)
  ...


Instance 1:
# teardown


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
# teardown
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 2:
not ok 191 must not receive too many peer availabilities
  ---
    operator: ok
    expected: true


Instance 2:
    actual:   false
    at: null._onTimeout (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js:501:9)
  ...


Instance 2:
# teardown


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 191 error should be null
ok 192 error should be null


Instance 2:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 192 error should be null
ok 193 error should be null
# setup


Instance 1:
# setup


Instance 3:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 3:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 3:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}


Instance 3:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 3:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
ok 191 error should be null


Instance 3:
ok 192 error should be null


Instance 3:
# setup


2016-03-29T08:08:41.681Z - warn: Failed on ios test: 40. peer should be found once after listening and discovery started


2016-03-29T08:08:41.681Z - info: Running on ios test: 41. Can call start/stopListeningForAdvertisements


Instance 3:
# 41. Can call start/stopListeningForAdvertisements


Instance 2:
# 41. Can call start/stopListeningForAdvertisements


Instance 1:
# 41. Can call start/stopListeningForAdvertisements


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
ok 193 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 194 Can call stopListeningForAdvertisements without error


Instance 1:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 194 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 195 Can call stopListeningForAdvertisements without error
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 193 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 194 Can call stopListeningForAdvertisements without error
# teardown


Instance 1:
ok 195 Should be able to call stopListeningForAdvertisments in teardown
ok 196 Should be able to call stopAdvertisingAndListening in teardown
# setup


Instance 2:
ok 196 Should be able to call stopListeningForAdvertisments in teardown
ok 197 Should be able to call stopAdvertisingAndListening in teardown
# setup


Instance 3:
ok 195 Should be able to call stopListeningForAdvertisments in teardown


Instance 3:
ok 196 Should be able to call stopAdvertisingAndListening in teardown


Instance 3:
# setup


2016-03-29T08:08:41.696Z - info: Running on ios test: 42. Calling startListeningForAdvertisements twice is NOT an error


Instance 1:
# 42. Calling startListeningForAdvertisements twice is NOT an error


Instance 2:
# 42. Calling startListeningForAdvertisements twice is NOT an error


Instance 3:
# 42. Calling startListeningForAdvertisements twice is NOT an error


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 197 Can call startListeningForAdvertisements without error
ok 198 Can call startListeningForAdvertisements twice without error
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 197 Can call startListeningForAdvertisements without error
ok 198 Can call startListeningForAdvertisements twice without error
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
ok 198 Can call startListeningForAdvertisements without error


Instance 2:
ok 199 Can call startListeningForAdvertisements twice without error


Instance 2:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 199 Should be able to call stopListeningForAdvertisments in teardown
ok 200 Should be able to call stopAdvertisingAndListening in teardown
# setup


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 199 Should be able to call stopListeningForAdvertisments in teardown
ok 200 Should be able to call stopAdvertisingAndListening in teardown
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 200 Should be able to call stopListeningForAdvertisments in teardown
ok 201 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
# setup


2016-03-29T08:08:41.713Z - info: Running on ios test: 43. Can call start/stopUpdateAdvertisingAndListening


Instance 3:
# 43. Can call start/stopUpdateAdvertisingAndListening


Instance 1:
# 43. Can call start/stopUpdateAdvertisingAndListening


Instance 2:
# 43. Can call start/stopUpdateAdvertisingAndListening


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 201 Can call startUpdateAdvertisingAndListening without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 202 Can call stopAdvertisingAndListening without error


Instance 1:
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 201 Can call startUpdateAdvertisingAndListening without error


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 202 Can call startUpdateAdvertisingAndListening without error


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 203 Can call stopAdvertisingAndListening without error
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
ok 202 Can call stopAdvertisingAndListening without error
# teardown


Instance 1:
ok 203 Should be able to call stopListeningForAdvertisments in teardown
ok 204 Should be able to call stopAdvertisingAndListening in teardown
# setup


Instance 3:
ok 203 Should be able to call stopListeningForAdvertisments in teardown
ok 204 Should be able to call stopAdvertisingAndListening in teardown
# setup


Instance 2:
ok 204 Should be able to call stopListeningForAdvertisments in teardown
ok 205 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
# setup


2016-03-29T08:08:41.740Z - info: Running on ios test: 44. Calling startUpdateAdvertisingAndListening twice is NOT an error


Instance 3:
# 44. Calling startUpdateAdvertisingAndListening twice is NOT an error


Instance 1:
# 44. Calling startUpdateAdvertisingAndListening twice is NOT an error


Instance 2:
# 44. Calling startUpdateAdvertisingAndListening twice is NOT an error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 205 Can call startUpdateAdvertisingAndListening without error


Instance 1:
ok 206 Can call startUpdateAdvertisingAndListening twice without error
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 206 Can call startUpdateAdvertisingAndListening without error


Instance 2:
ok 207 Can call startUpdateAdvertisingAndListening twice without error
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 205 Can call startUpdateAdvertisingAndListening without error


Instance 3:
ok 206 Can call startUpdateAdvertisingAndListening twice without error


Instance 3:
# teardown


Instance 1:
ok 207 Should be able to call stopListeningForAdvertisments in teardown


Instance 2:
ok 208 Should be able to call stopListeningForAdvertisments in teardown


Instance 3:
ok 207 Should be able to call stopListeningForAdvertisments in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 208 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 209 Should be able to call stopAdvertisingAndListening in teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 208 Should be able to call stopAdvertisingAndListening in teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:08:41.767Z - info: Running on ios test: 45. peerAvailabilityChange is called


Instance 1:
# 45. peerAvailabilityChange is called


Instance 3:
# 45. peerAvailabilityChange is called


Instance 2:
# 45. peerAvailabilityChange is called


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 210 Can call startUpdateAdvertisingAndListeningwithout error


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 209 Can call startUpdateAdvertisingAndListeningwithout error


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
ok 211 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 209 Can call startUpdateAdvertisingAndListeningwithout error


Instance 3:
ok 210 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 210 Can call startListeningForAdvertisements without error


Instance 2:
ok 212 peers must be an array


Instance 1:
ok 211 peers must be an array


Instance 1:
ok 212 peers must not be zero-length


Instance 1:
ok 213 peer must have peerIdentifier


Instance 1:
ok 214 peerIdentifier must be a string


Instance 1:
ok 215 peer must have peerAvailable


Instance 3:
ok 211 peers must be an array


Instance 1:
ok 216 peer must have pleaseConnect


Instance 2:
ok 213 peers must not be zero-length


Instance 2:
ok 214 peer must have peerIdentifier


Instance 3:
ok 212 peers must not be zero-length


Instance 2:
ok 215 peerIdentifier must be a string


Instance 2:
ok 216 peer must have peerAvailable


Instance 2:
ok 217 peer must have pleaseConnect


Instance 1:
# teardown


Instance 3:
ok 213 peer must have peerIdentifier


Instance 3:
ok 214 peerIdentifier must be a string


Instance 3:
ok 215 peer must have peerAvailable


Instance 3:
ok 216 peer must have pleaseConnect


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
ok 217 Should be able to call stopListeningForAdvertisments in teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 217 Should be able to call stopListeningForAdvertisments in teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 218 Should be able to call stopListeningForAdvertisments in teardown


Instance 1:
ok 218 Should be able to call stopAdvertisingAndListening in teardown


Instance 1:
# setup


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
ok 218 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 219 Should be able to call stopAdvertisingAndListening in teardown


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:41.802Z - info: Running on ios test: 46. Can connect to a remote peer


Instance 1:
# 46. Can connect to a remote peer


Instance 3:
# 46. Can connect to a remote peer


Instance 2:
# 46. Can connect to a remote peer


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 219 Can call startUpdateAdvertisingAndListening without error


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 3:
ok 220 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
ok 219 Can call startUpdateAdvertisingAndListening without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 220 Can call startListeningForAdvertisements without error


Instance 3:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:34914848-f7ae-4a93-bcc6-605691e7b6a7","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 220 Can call startUpdateAdvertisingAndListening without error


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
ok 221 Can call startListeningForAdvertisements without error


Instance 3:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:37ffbe45-2c9b-4b1f-8e28-5f75bdfdaf69","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:37ffbe45-2c9b-4b1f-8e28-5f75bdfdaf69","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 3:
INFO testThaliMobileNative: 


Instance 3:
ok 221 Must have listeningPort


Instance 3:
ok 222 listeningPort must be a number


Instance 3:
ok 223 Connection must have clientPort


Instance 3:
ok 224 clientPort must be a number


Instance 3:
ok 225 Connection must have serverPort


Instance 3:
ok 226 serverPort must be a number


Instance 3:
ok 227 forward connection must have clientPort == 0


Instance 3:
ok 228 forward connection must have serverPort == 0


Instance 3:
# teardown


Instance 1:
INFO testThaliMobileNative: 


Instance 1:
ok 221 Must have listeningPort


Instance 1:
ok 222 listeningPort must be a number


Instance 1:
ok 223 Connection must have clientPort


Instance 1:
ok 224 clientPort must be a number


Instance 1:
ok 225 Connection must have serverPort


Instance 1:
ok 226 serverPort must be a number


Instance 1:
ok 227 forward connection must have clientPort == 0


Instance 1:
ok 228 forward connection must have serverPort == 0


Instance 1:
# teardown


Instance 3:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:34914848-f7ae-4a93-bcc6-605691e7b6a7","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:34914848-f7ae-4a93-bcc6-605691e7b6a7","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:85c16da3-2b24-4a14-b282-9455f99d2d20","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:85c16da3-2b24-4a14-b282-9455f99d2d20","peerAvailable":true,"pleaseConnect":false}]


Instance 3:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:37ffbe45-2c9b-4b1f-8e28-5f75bdfdaf69","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:37ffbe45-2c9b-4b1f-8e28-5f75bdfdaf69","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 2:
INFO testThaliMobileNative: 


Instance 2:
ok 222 Must have listeningPort


Instance 2:
ok 223 listeningPort must be a number


Instance 2:
ok 224 Connection must have clientPort


Instance 2:
ok 225 clientPort must be a number


Instance 2:
ok 226 Connection must have serverPort


Instance 2:
ok 227 serverPort must be a number


Instance 2:
ok 228 forward connection must have clientPort == 0


Instance 2:
ok 229 forward connection must have serverPort == 0


Instance 2:
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 229 Should be able to call stopListeningForAdvertisments in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 230 Should be able to call stopListeningForAdvertisments in teardown


Instance 1:
ok 229 Should be able to call stopListeningForAdvertisments in teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
ok 230 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 231 Should be able to call stopAdvertisingAndListening in teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 230 Should be able to call stopAdvertisingAndListening in teardown


Instance 1:
# setup


2016-03-29T08:08:42.459Z - info: Running on ios test: 47. Can shift large amounts of data


Instance 1:
# 47. Can shift large amounts of data


Instance 3:
# 47. Can shift large amounts of data


Instance 2:
# 47. Can shift large amounts of data


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 232 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 233 Can call startListeningForAdvertisements without error


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 231 Can call startUpdateAdvertisingAndListening without error


Instance 1:
ok 231 Can call startUpdateAdvertisingAndListening without error


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 232 Can call startListeningForAdvertisements without error


Instance 3:
ok 232 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 3:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 3:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 2:
INFO testThaliMobileNative: 


Instance 3:
INFO testThaliMobileNative: 
INFO testThaliMobileNative: Forward connection


Instance 2:
INFO testThaliMobileNative: Forward connection


Instance 3:
INFO testThaliMobileNative: forwardSend


Instance 2:
INFO testThaliMobileNative: forwardSend


Instance 1:
INFO testThaliMobileNative: 


Instance 1:
INFO testThaliMobileNative: Forward connection


Instance 1:
INFO testThaliMobileNative: forwardSend


Instance 2:
INFO testThaliMobileNative: forwardData


Instance 2:
ok 234 received should match sent forward


Instance 3:
INFO testThaliMobileNative: forwardData


Instance 3:
ok 233 received should match sent forward


Instance 3:
# teardown


Instance 1:
INFO testThaliMobileNative: forwardData


Instance 1:
ok 233 received should match sent forward


Instance 2:
# teardown


Instance 1:
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
ok 234 Should be able to call stopListeningForAdvertisments in teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 235 Should be able to call stopAdvertisingAndListening in teardown


Instance 3:
# setup


Instance 1:
ok 234 Should be able to call stopListeningForAdvertisments in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 235 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
ok 235 Should be able to call stopListeningForAdvertisments in teardown


Instance 1:
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 236 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
# setup


2016-03-29T08:08:42.606Z - info: Running on ios test: 48. #startListeningForAdvertisements should fail if start not called


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 48. #startListeningForAdvertisements should fail if start not called


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 48. #startListeningForAdvertisements should fail if start not called


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
ok 236 specific error should be returned
# teardown


Instance 3:
ok 236 specific error should be returned
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 48. #startListeningForAdvertisements should fail if start not called


Instance 2:
ok 237 specific error should be returned


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:43.629Z - info: Running on ios test: 49. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 49. #startUpdateAdvertisingAndListening should fail if start not called


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 49. #startUpdateAdvertisingAndListening should fail if start not called


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 49. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
ok 237 specific error should be returned
# teardown


Instance 2:
ok 238 specific error should be returned
# teardown


Instance 3:
ok 237 specific error should be returned
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:43.648Z - info: Running on ios test: 50. should be able to call #stopListeningForAdvertisements many times


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 50. should be able to call #stopListeningForAdvertisements many times


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 50. should be able to call #stopListeningForAdvertisements many times


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 50. should be able to call #stopListeningForAdvertisements many times


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50583
ok 239 no errors
ok 240 still no errors
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50584
ok 238 no errors
ok 239 still no errors
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50586


Instance 3:
ok 238 no errors


Instance 3:
ok 239 still no errors


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:43.668Z - info: Running on ios test: 51. should be able to call #startListeningForAdvertisements many times


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 51. should be able to call #startListeningForAdvertisements many times


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 51. should be able to call #startListeningForAdvertisements many times


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 51. should be able to call #startListeningForAdvertisements many times


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50589
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 240 no errors
ok 241 still no errors
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50590
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 241 no errors
ok 242 still no errors
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50592


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
ok 240 no errors
ok 241 still no errors


Instance 3:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
# setup


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
# setup


2016-03-29T08:08:43.689Z - info: Running on ios test: 52. should be able to call #startUpdateAdvertisingAndListening many times


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 52. should be able to call #startUpdateAdvertisingAndListening many times


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 52. should be able to call #startUpdateAdvertisingAndListening many times


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 52. should be able to call #startUpdateAdvertisingAndListening many times


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50595
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 242 no errors


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50596


Instance 3:
ok 243 still no errors


Instance 3:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
ok 242 no errors


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50602


Instance 1:
ok 243 still no errors


Instance 1:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 243 no errors


Instance 2:
ok 244 still no errors


Instance 2:
# teardown


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
# setup


2016-03-29T08:08:43.719Z - info: Running on ios test: 53. should be able to call #stopAdvertisingAndListening many times


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 53. should be able to call #stopAdvertisingAndListening many times


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 53. should be able to call #stopAdvertisingAndListening many times


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 53. should be able to call #stopAdvertisingAndListening many times


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50606


Instance 1:
ok 244 no errors
ok 245 still no errors
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50608


Instance 3:
ok 244 no errors


Instance 3:
ok 245 still no errors


Instance 3:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50610


Instance 2:
ok 245 no errors


Instance 2:
ok 246 still no errors


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:43.744Z - info: Running on ios test: 54. can get the network status before starting


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 54. can get the network status before starting


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 54. can get the network status before starting


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 54. can get the network status before starting


Instance 3:
ok 246 network status should have certain non-empty properties


Instance 3:
# teardown


Instance 1:
ok 246 network status should have certain non-empty properties


Instance 1:
# teardown


Instance 2:
ok 247 network status should have certain non-empty properties


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:43.767Z - info: Running on ios test: 55. error returned with bad router


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 55. error returned with bad router


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 55. error returned with bad router


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 55. error returned with bad router


Instance 1:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string


Instance 1:
ok 247 specific error expected
# teardown


Instance 3:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string


Instance 3:
ok 247 specific error expected


Instance 3:
# teardown


Instance 2:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string


Instance 2:
ok 248 specific error expected


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:43.791Z - info: Running on ios test: 56. all services are stopped when we call stop


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 56. all services are stopped when we call stop


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 56. all services are stopped when we call stop


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 56. all services are stopped when we call stop


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50612
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50615


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 248 connection to servers manager should succeed after starting


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 1:
ok 249 connection to router server should succeed after starting


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
ok 248 connection to servers manager should succeed after starting


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 250 is stopped after calling stop


Instance 1:
ok 251 connection to servers manager should fail after stopping


Instance 1:
ok 252 connection to router server should fail after stopping


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50627


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
ok 249 connection to router server should succeed after starting
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
ok 249 connection to servers manager should succeed after starting


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 250 is stopped after calling stop


Instance 3:
ok 251 connection to servers manager should fail after stopping


Instance 3:
ok 252 connection to router server should fail after stopping


Instance 3:
# teardown


Instance 2:
ok 250 connection to router server should succeed after starting


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 251 is stopped after calling stop


Instance 2:
ok 252 connection to servers manager should fail after stopping


Instance 2:
ok 253 connection to router server should fail after stopping


Instance 2:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:08:43.844Z - info: Running on ios test: 57. make sure terminateConnection is properly hooked up


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
# 57. make sure terminateConnection is properly hooked up


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 57. make sure terminateConnection is properly hooked up


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 57. make sure terminateConnection is properly hooked up


Instance 2:
ok 254 called with right arguments
# teardown


Instance 3:
ok 253 called with right arguments


Instance 3:
# teardown


Instance 1:
ok 253 called with right arguments


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:08:43.863Z - info: Running on ios test: 58. make sure terminateListener is properly hooked up


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 58. make sure terminateListener is properly hooked up


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 58. make sure terminateListener is properly hooked up


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 58. make sure terminateListener is properly hooked up


Instance 2:
ok 255 called with right arguments
# teardown


Instance 3:
ok 254 called with right arguments


Instance 3:
# teardown


Instance 1:
ok 254 called with right arguments


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:08:43.882Z - info: Running on ios test: 59. make sure we actually call kill connections properly


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 59. make sure we actually call kill connections properly


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 59. make sure we actually call kill connections properly


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 59. make sure we actually call kill connections properly


Instance 3:
ok 255 IMPLEMENT ME!!!!!!
# teardown


Instance 2:
ok 256 IMPLEMENT ME!!!!!!
# teardown


Instance 1:
ok 255 IMPLEMENT ME!!!!!!


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:08:43.902Z - info: Running on ios test: 60. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 60. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
# 60. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 60. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received


Instance 2:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50637


Instance 2:
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50636,"error":{}}
ok 257 failure reason is as expected
ok 258 error description is as expected
ok 259 must be stopped
# teardown


Instance 3:
DEBUG createNativeListener: listening 50639
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50638,"error":{}}


Instance 3:
ok 256 failure reason is as expected


Instance 3:
ok 257 error description is as expected


Instance 3:
ok 258 must be stopped


Instance 3:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50641
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50640,"error":{}}
ok 256 failure reason is as expected
ok 257 error description is as expected


Instance 1:
ok 258 must be stopped
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:44.932Z - info: Running on ios test: 61. We repeat failedConnection event when we get it from thaliTcpServersManager


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 61. We repeat failedConnection event when we get it from thaliTcpServersManager


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 61. We repeat failedConnection event when we get it from thaliTcpServersManager


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 61. We repeat failedConnection event when we get it from thaliTcpServersManager


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50644
ok 259 peerIdentifier matches
ok 260 error description matches
# teardown


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50645
ok 259 peerIdentifier matches
ok 260 error description matches
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50647


Instance 2:
ok 260 peerIdentifier matches


Instance 2:
ok 261 error description matches


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:44.951Z - info: Running on ios test: 62. can do HTTP requests between peers without coordinator


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 62. can do HTTP requests between peers without coordinator


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 62. can do HTTP requests between peers without coordinator


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 62. can do HTTP requests between peers without coordinator


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50650
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 261 found a peer! {"peerIdentifier":"foo","portNumber":50656,"hostAddress":"127.0.0.1"}


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50651
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 262 found a peer! {"peerIdentifier":"foo","portNumber":50657,"hostAddress":"127.0.0.1"}


Instance 2:
DEBUG createPeerListener: first connection


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50663


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG createPeerListener: first connection


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
ok 261 found a peer! {"peerIdentifier":"foo","portNumber":50666,"hostAddress":"127.0.0.1"}


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: first connection


Instance 2:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 2:
DEBUG createPeerListener: forward connection


Instance 3:
DEBUG createPeerListener: forward connection


Instance 1:
DEBUG createPeerListener: forward connection


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 262 Should only get expected id


Instance 3:
ok 262 Should only get expected id


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed


Instance 3:
DEBUG createNativeListener: stream close:


Instance 1:
ok 263 server should return 200


Instance 3:
DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed


Instance 1:
ok 264 response body should match testData


Instance 3:
ok 263 server should return 200


Instance 1:
# teardown


Instance 3:
ok 264 response body should match testData


Instance 3:
# teardown


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
ok 263 Should only get expected id


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed


Instance 2:
ok 264 server should return 200


Instance 2:
ok 265 response body should match testData


Instance 2:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
DEBUG createNativeListener: mux close


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
# setup


Instance 1:
# setup


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 2:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
# setup


2016-03-29T08:08:45.158Z - info: Running on ios test: 63. make sure bad PSK connections fail


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 63. make sure bad PSK connections fail


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 63. make sure bad PSK connections fail


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
ok 265 FIX ME, PLEASE!!!


Instance 3:
# 63. make sure bad PSK connections fail


Instance 1:
# teardown


Instance 2:
ok 266 FIX ME, PLEASE!!!


Instance 2:
# teardown


Instance 3:
ok 265 FIX ME, PLEASE!!!


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:46.192Z - info: Running on ios test: 64. peer changes handled from a queue


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 64. peer changes handled from a queue


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 64. peer changes handled from a queue


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 64. peer changes handled from a queue


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50687
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 266 peers were handled in the right order
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50688
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 267 peers were handled in the right order
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50710


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
ok 266 peers were handled in the right order


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:46.225Z - info: Running on ios test: 65. relaying discoveryAdvertisingStateUpdateNonTCP


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 65. relaying discoveryAdvertisingStateUpdateNonTCP


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
# 65. relaying discoveryAdvertisingStateUpdateNonTCP


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 65. relaying discoveryAdvertisingStateUpdateNonTCP


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50723
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 267 discovery is active
ok 268 advertising is active
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50724
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 268 discovery is active
ok 269 advertising is active
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50726


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 267 discovery is active


Instance 3:
ok 268 advertising is active


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:46.245Z - info: Running on ios test: 66. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 66. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
# 66. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 66. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50729
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50729
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50730
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50730


Instance 1:
ok 269 right error reason
ok 270 Stop should be fine
ok 271 same port
ok 272 we should be off
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 270 right error reason
ok 271 Stop should be fine
ok 272 same port
ok 273 we should be off
# teardown


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50736


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 3:
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50736


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 3:
ok 269 right error reason


Instance 3:
ok 270 Stop should be fine


Instance 3:
ok 271 same port


Instance 3:
ok 272 we should be off


Instance 3:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:46.271Z - info: Running on ios test: 67. we successfully receive and replay discoveryAdvertisingStateUpdate


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 67. we successfully receive and replay discoveryAdvertisingStateUpdate


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 67. we successfully receive and replay discoveryAdvertisingStateUpdate


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 67. we successfully receive and replay discoveryAdvertisingStateUpdate


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50741
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 273 discoveryActive matches
ok 274 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 275 discoveryActive matches
ok 276 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50745
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 277 discoveryActive matches
ok 278 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 279 discoveryActive matches
ok 280 advertisingActive matches


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50742
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 274 discoveryActive matches
ok 275 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 276 discoveryActive matches
ok 277 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50746
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 278 discoveryActive matches
ok 279 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 280 discoveryActive matches
ok 281 advertisingActive matches


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50752
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50754
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 273 discoveryActive matches
ok 274 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 275 discoveryActive matches
ok 276 advertisingActive matches


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50756
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50758


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
ok 277 discoveryActive matches
ok 278 advertisingActive matches


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 279 discoveryActive matches


Instance 1:
ok 280 advertisingActive matches


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50762


Instance 1:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:46.306Z - info: Running on ios test: 68. can do HTTP requests between peers


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 68. can do HTTP requests between peers


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 68. can do HTTP requests between peers


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 1:
# 68. can do HTTP requests between peers


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50764


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50768


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50771


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 282 found a peer! {"peerIdentifier":"urn:uuid:d474a378-727f-4aaf-b4aa-637508a83558","portNumber":50774,"hostAddress":"127.0.0.1"}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
DEBUG createPeerListener: first connection


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
ok 281 found a peer! {"peerIdentifier":"urn:uuid:d474a378-727f-4aaf-b4aa-637508a83558","portNumber":50780,"hostAddress":"127.0.0.1"}


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 3:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
DEBUG createPeerListener: pleaseConnect= false


Instance 3:
ok 281 found a peer! {"peerIdentifier":"urn:uuid:75592154-496f-4151-9de6-6764bb334095","portNumber":50783,"hostAddress":"127.0.0.1"}


Instance 1:
DEBUG createPeerListener: first connection


Instance 3:
DEBUG createPeerListener: first connection


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux


Instance 3:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 2:
DEBUG createPeerListener: forward connection


Instance 1:
DEBUG createPeerListener: forward connection


Instance 3:
DEBUG createPeerListener: forward connection


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 3:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 3:
DEBUG createNativeListener: new outgoing socket


Instance 3:
ok 282 Should only get expected id


Instance 1:
ok 282 Should only get expected id


Instance 3:
ok 283 Should only get expected id


Instance 3:
DEBUG createNativeListener: stream close:


Instance 2:
ok 283 server should return 200


Instance 2:
ok 284 response body should match testData


Instance 2:
# teardown


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 3:
ok 284 server should return 200


Instance 3:
ok 285 response body should match testData


Instance 3:
# teardown


Instance 3:
DEBUG createNativeListener: stream close:


Instance 1:
ok 283 server should return 200


Instance 1:
ok 284 response body should match testData


Instance 1:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
# setup


Instance 3:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 1:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 3:
DEBUG createNativeListener: mux close


Instance 3:
DEBUG createNativeListener: incoming socket close


Instance 3:
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
# setup


2016-03-29T08:08:46.490Z - info: Running on ios test: 69. will fail bad PSK connection between peers


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# 69. will fail bad PSK connection between peers


Instance 3:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 3:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 3:
# 69. will fail bad PSK connection between peers


Instance 1:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native


Instance 1:
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native


Instance 2:
ok 285 FIX ME, PLEASE!!!


Instance 2:
# teardown


Instance 3:
ok 286 FIX ME, PLEASE!!!


Instance 3:
# teardown


Instance 1:
# 69. will fail bad PSK connection between peers


Instance 1:
ok 285 FIX ME, PLEASE!!!


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:47.522Z - info: Running on ios test: 70. Client to server request locally


Instance 2:
# 70. Client to server request locally


Instance 3:
# 70. Client to server request locally


Instance 1:
# 70. Client to server request locally


Instance 1:
startUpdateAdvertisingAndListening
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50797
_peerAvailabilityChanged - end


Instance 3:
startUpdateAdvertisingAndListening
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50798
_peerAvailabilityChanged - end


Instance 1:
ok 286 Host address must match


Instance 1:
ok 287 suggestedTCPTimeout must match
ok 288 connectionType must match
ok 289 portNumber must match


Instance 1:
stopAdvertisingAndListening


Instance 1:
# teardown


Instance 3:
ok 287 Host address must match


Instance 3:
ok 288 suggestedTCPTimeout must match


Instance 2:
startUpdateAdvertisingAndListening


Instance 3:
ok 289 connectionType must match


Instance 3:
ok 290 portNumber must match


Instance 2:
_peerAvailabilityChanged


Instance 2:
peerIdentifier:id123


Instance 2:
connectionType:tcp


Instance 2:
hostAddress:127.0.0.1


Instance 2:
portNumber:50801
_peerAvailabilityChanged - end


Instance 3:
stopAdvertisingAndListening


Instance 3:
# teardown


Instance 2:
ok 286 Host address must match
ok 287 suggestedTCPTimeout must match


Instance 2:
ok 288 connectionType must match


Instance 2:
ok 289 portNumber must match


Instance 2:
stopAdvertisingAndListening


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:47.578Z - info: Running on ios test: 71. Test BEACONS_RETRIEVED_AND_PARSED locally


Instance 1:
# 71. Test BEACONS_RETRIEVED_AND_PARSED locally


Instance 2:
# 71. Test BEACONS_RETRIEVED_AND_PARSED locally


Instance 3:
# 71. Test BEACONS_RETRIEVED_AND_PARSED locally


Instance 1:
ok 290 peerIdentifier should be identifier


Instance 1:
ok 291 Response should be BEACONS_RETRIEVED_AND_PARSED


Instance 1:
ok 292 good beacon
ok 293 good preAmble


Instance 1:
ok 294 public keys match!


Instance 1:
ok 295 must return null after successful call


Instance 1:
# teardown


Instance 2:
ok 290 peerIdentifier should be identifier


Instance 2:
ok 291 Response should be BEACONS_RETRIEVED_AND_PARSED


Instance 2:
ok 292 good beacon


Instance 2:
ok 293 good preAmble


Instance 2:
ok 294 public keys match!


Instance 2:
ok 295 must return null after successful call


Instance 2:
# teardown


Instance 3:
ok 291 peerIdentifier should be identifier


Instance 3:
ok 292 Response should be BEACONS_RETRIEVED_AND_PARSED


Instance 3:
ok 293 good beacon


Instance 3:
ok 294 good preAmble


Instance 3:
ok 295 public keys match!


Instance 3:
ok 296 must return null after successful call


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:47.620Z - info: Running on ios test: 72. Test HTTP_BAD_RESPONSE locally


Instance 1:
# 72. Test HTTP_BAD_RESPONSE locally


Instance 2:
# 72. Test HTTP_BAD_RESPONSE locally


Instance 3:
# 72. Test HTTP_BAD_RESPONSE locally


Instance 2:
ok 296 Response should be HTTP_BAD_RESPONSE


Instance 1:
ok 296 Response should be HTTP_BAD_RESPONSE


Instance 1:
ok 297 must return null after successful call


Instance 1:
# teardown


Instance 2:
ok 297 must return null after successful call


Instance 2:
# teardown


Instance 3:
ok 297 Response should be HTTP_BAD_RESPONSE


Instance 3:
ok 298 must return null after successful call


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:47.655Z - info: Running on ios test: 73. Test NETWORK_PROBLEM locally


Instance 1:
# 73. Test NETWORK_PROBLEM locally


Instance 2:
# 73. Test NETWORK_PROBLEM locally


Instance 3:
# 73. Test NETWORK_PROBLEM locally


Instance 2:
ok 298 Response should be NETWORK_PROBLEM
ok 299 reject reason should be: Could not establish TCP connection
# teardown


Instance 1:
ok 298 Response should be NETWORK_PROBLEM
ok 299 reject reason should be: Could not establish TCP connection
# teardown


Instance 3:
ok 299 Response should be NETWORK_PROBLEM


Instance 3:
ok 300 reject reason should be: Could not establish TCP connection


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:47.686Z - info: Running on ios test: 74. Test timeout locally


Instance 1:
# 74. Test timeout locally


Instance 2:
# 74. Test timeout locally


Instance 3:
# 74. Test timeout locally


Instance 1:
ok 300 Should be NETWORK_PROBLEM caused by timeout
ok 301 reject reason should be Could not establish TCP connection


Instance 2:
ok 300 Should be NETWORK_PROBLEM caused by timeout
ok 301 reject reason should be Could not establish TCP connection


Instance 3:
ok 301 Should be NETWORK_PROBLEM caused by timeout
ok 302 reject reason should be Could not establish TCP connection


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:48.725Z - info: Running on ios test: 75. Call the start two times


Instance 2:
# 75. Call the start two times


Instance 1:
# 75. Call the start two times


Instance 3:
# 75. Call the start two times


Instance 3:
ok 303 Call start once


Instance 1:
ok 302 Call start once


Instance 2:
ok 302 Call start once


Instance 2:
ok 303 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 304 must return null after successful call.
# teardown


Instance 3:
ok 304 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 305 must return null after successful call.


Instance 3:
# teardown


Instance 1:
ok 303 Response should be BEACONS_RETRIEVED_AND_PARSED


Instance 1:
ok 304 must return null after successful call.


Instance 1:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:48.760Z - info: Running on ios test: 76. Call the kill before calling the start


Instance 1:
# 76. Call the kill before calling the start


Instance 2:
# 76. Call the kill before calling the start


Instance 3:
# 76. Call the kill before calling the start


Instance 3:
ok 306 Should be Killed
ok 307 Start after killed
# teardown


Instance 1:
ok 305 Should be Killed
ok 306 Start after killed


Instance 2:
ok 305 Should be Killed
ok 306 Start after killed
# teardown


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:48.785Z - info: Running on ios test: 77. Call the kill immediately after the start


Instance 1:
# 77. Call the kill immediately after the start


Instance 2:
# 77. Call the kill immediately after the start


Instance 3:
# 77. Call the kill immediately after the start


Instance 3:
ok 308 Should be KILLED
ok 309 must return null after successful kill


Instance 3:
# teardown


Instance 2:
ok 307 Should be KILLED
ok 308 must return null after successful kill


Instance 1:
ok 307 Should be KILLED


Instance 2:
# teardown


Instance 1:
ok 308 must return null after successful kill


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:08:48.814Z - info: Running on ios test: 78. Call the kill while waiting a response from the server


Instance 3:
# 78. Call the kill while waiting a response from the server


Instance 2:
# 78. Call the kill while waiting a response from the server


Instance 1:
# 78. Call the kill while waiting a response from the server


Instance 2:
ok 309 Should be KILLED
ok 310 must return null after successful kill


Instance 3:
ok 310 Should be KILLED
ok 311 must return null after successful kill


Instance 2:
# teardown


Instance 1:
ok 309 Should be KILLED
ok 310 must return null after successful kill


Instance 3:
# teardown


Instance 1:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:50.854Z - info: Running on ios test: 79. Test to exceed the max content size locally


Instance 1:
# 79. Test to exceed the max content size locally


Instance 3:
# 79. Test to exceed the max content size locally


Instance 2:
# 79. Test to exceed the max content size locally


Instance 3:
ok 312 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 313 must return null after successful call


Instance 1:
ok 311 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 312 must return null after successful call
# teardown


Instance 3:
# teardown


Instance 2:
ok 311 HTTP_BAD_RESPONSE should be response when content size is exceeded


Instance 2:
ok 312 must return null after successful call


Instance 2:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:50.886Z - info: Running on ios test: 80. Close the server socket while the client is waiting a response from the server. Local test.


Instance 1:
# 80. Close the server socket while the client is waiting a response from the server. Local test.


Instance 3:
# 80. Close the server socket while the client is waiting a response from the server. Local test.


Instance 2:
# 80. Close the server socket while the client is waiting a response from the server. Local test.


Instance 1:
ok 313 Should be NETWORK_PROBLEM caused closing server socket
ok 314 Should be Could not establish TCP connection
# teardown


Instance 3:
ok 314 Should be NETWORK_PROBLEM caused closing server socket
ok 315 Should be Could not establish TCP connection
# teardown


Instance 2:
ok 313 Should be NETWORK_PROBLEM caused closing server socket
ok 314 Should be Could not establish TCP connection


Instance 2:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:52.926Z - info: Running on ios test: 81. Close the client socket while the client is waiting a response from the server. Local test.


Instance 1:
# 81. Close the client socket while the client is waiting a response from the server. Local test.


Instance 2:
# 81. Close the client socket while the client is waiting a response from the server. Local test.


Instance 3:
# 81. Close the client socket while the client is waiting a response from the server. Local test.


Instance 2:
ok 315 Should be NETWORK_PROBLEM caused closing client socket
ok 316 Should be Could not establish TCP connection
# teardown


Instance 1:
ok 315 Should be NETWORK_PROBLEM caused closing client socket
ok 316 Should be Could not establish TCP connection
# teardown


Instance 3:
ok 316 Should be NETWORK_PROBLEM caused closing client socket
ok 317 Should be Could not establish TCP connection


Instance 3:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:54.966Z - info: Running on ios test: 82. #generatePreambleAndBeacons bad args


Instance 1:
# 82. #generatePreambleAndBeacons bad args


Instance 2:
# 82. #generatePreambleAndBeacons bad args


Instance 3:
# 82. #generatePreambleAndBeacons bad args


Instance 1:
ok 317 publicKeysToNotify cannot be null
ok 318 ecdh for local device cannot be null
ok 319 milliseconds cannot be less than 0
ok 320 milliseconds cannot be 0
ok 321 milliseconds cannot be greater than one_day
# teardown


Instance 2:
ok 317 publicKeysToNotify cannot be null
ok 318 ecdh for local device cannot be null
ok 319 milliseconds cannot be less than 0
ok 320 milliseconds cannot be 0
ok 321 milliseconds cannot be greater than one_day
# teardown


Instance 3:
ok 318 publicKeysToNotify cannot be null
ok 319 ecdh for local device cannot be null
ok 320 milliseconds cannot be less than 0
ok 321 milliseconds cannot be 0


Instance 3:
ok 322 milliseconds cannot be greater than one_day


Instance 3:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:08:54.984Z - info: Running on ios test: 83. #generatePreambleAndBeacons empty keys to notify


Instance 3:
# 83. #generatePreambleAndBeacons empty keys to notify


Instance 1:
# 83. #generatePreambleAndBeacons empty keys to notify


Instance 2:
# 83. #generatePreambleAndBeacons empty keys to notify


Instance 1:
ok 322 should be equal
# teardown


Instance 2:
ok 322 should be equal
# teardown


Instance 3:
ok 323 should be equal
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:08:55.001Z - info: Running on ios test: 84. #generatePreambleAndBeacons multiple keys to notify


Instance 3:
# 84. #generatePreambleAndBeacons multiple keys to notify


Instance 1:
# 84. #generatePreambleAndBeacons multiple keys to notify


Instance 2:
# 84. #generatePreambleAndBeacons multiple keys to notify


Instance 2:
ok 323 should be equal
ok 324 should be equal
ok 325 (unnamed assert)
ok 326 should be equal
# teardown


Instance 1:
ok 323 should be equal
ok 324 should be equal
ok 325 (unnamed assert)
ok 326 should be equal
# teardown


Instance 3:
ok 324 should be equal


Instance 3:
ok 325 should be equal


Instance 3:
ok 326 (unnamed assert)


Instance 3:
ok 327 should be equal


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:55.030Z - info: Running on ios test: 85. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble


Instance 3:
# 85. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble


Instance 1:
# 85. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble


Instance 2:
# 85. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble


Instance 3:
ok 328 should throw


Instance 1:
ok 327 should throw


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
ok 327 should throw


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:55.050Z - info: Running on ios test: 86. #parseBeacons invalid expiration in beaconStreamWithPreAmble


Instance 1:
# 86. #parseBeacons invalid expiration in beaconStreamWithPreAmble


Instance 2:
# 86. #parseBeacons invalid expiration in beaconStreamWithPreAmble


Instance 3:
# 86. #parseBeacons invalid expiration in beaconStreamWithPreAmble


Instance 1:
ok 328 Preamble expiration must be a 64 bit integer


Instance 1:
# teardown


Instance 3:
ok 329 Preamble expiration must be a 64 bit integer


Instance 2:
ok 328 Preamble expiration must be a 64 bit integer


Instance 2:
# teardown


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:08:55.069Z - info: Running on ios test: 87. #parseBeacons expiration out of range lower


Instance 3:
# 87. #parseBeacons expiration out of range lower


Instance 1:
# 87. #parseBeacons expiration out of range lower


Instance 2:
# 87. #parseBeacons expiration out of range lower


Instance 1:
ok 329 Expiration out of range


Instance 1:
# teardown


Instance 3:
ok 330 Expiration out of range


Instance 3:
# teardown


Instance 2:
ok 329 Expiration out of range


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.089Z - info: Running on ios test: 88. #parseBeacons expiration out of range lower


Instance 2:
# 88. #parseBeacons expiration out of range lower


Instance 1:
# 88. #parseBeacons expiration out of range lower


Instance 3:
# 88. #parseBeacons expiration out of range lower


Instance 2:
ok 330 Expiration out of range


Instance 2:
# teardown


Instance 1:
ok 330 Expiration out of range


Instance 3:
ok 331 Expiration out of range


Instance 1:
# teardown


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.115Z - info: Running on ios test: 89. #parseBeacons no beacons returns null


Instance 2:
# 89. #parseBeacons no beacons returns null


Instance 1:
# 89. #parseBeacons no beacons returns null


Instance 3:
# 89. #parseBeacons no beacons returns null


Instance 2:
ok 331 should be equal


Instance 1:
ok 331 should be equal


Instance 2:
# teardown


Instance 1:
# teardown


Instance 3:
ok 332 should be equal


Instance 3:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.132Z - info: Running on ios test: 90. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble


Instance 1:
# 90. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble


Instance 3:
# 90. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble


Instance 2:
# 90. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble


Instance 2:
ok 332 Malformed encrypted beacon key ID


Instance 2:
# teardown


Instance 1:
ok 332 Malformed encrypted beacon key ID


Instance 1:
# teardown


Instance 3:
ok 333 Malformed encrypted beacon key ID


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.148Z - info: Running on ios test: 91. #parseBeacons addressBookCallback fails decrypt


Instance 2:
# 91. #parseBeacons addressBookCallback fails decrypt


Instance 1:
# 91. #parseBeacons addressBookCallback fails decrypt


Instance 3:
# 91. #parseBeacons addressBookCallback fails decrypt


Instance 2:
ok 333 should be equal
# teardown


Instance 3:
ok 334 should be equal
# teardown


Instance 1:
ok 333 should be equal


Instance 1:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.184Z - info: Running on ios test: 92. #parseBeacons addressBookCallback returns no matches


Instance 1:
# 92. #parseBeacons addressBookCallback returns no matches


Instance 2:
# 92. #parseBeacons addressBookCallback returns no matches


Instance 3:
# 92. #parseBeacons addressBookCallback returns no matches


Instance 2:
ok 334 should be equal
ok 335 should be equal
# teardown


Instance 1:
ok 334 should be equal
ok 335 should be equal
# teardown


Instance 3:
ok 335 should be equal


Instance 3:
ok 336 should be equal


Instance 3:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.215Z - info: Running on ios test: 93. #parseBeacons addressBookCallback returns spurious match


Instance 1:
# 93. #parseBeacons addressBookCallback returns spurious match


Instance 2:
# 93. #parseBeacons addressBookCallback returns spurious match


Instance 3:
# 93. #parseBeacons addressBookCallback returns spurious match


Instance 2:
ok 336 should be equal
ok 337 should be equal
# teardown


Instance 3:
ok 337 should be equal
ok 338 should be equal
# teardown


Instance 1:
ok 336 should be equal


Instance 1:
ok 337 should be equal


Instance 1:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.245Z - info: Running on ios test: 94. #parseBeacons addressBookCallback returns public key


Instance 2:
# 94. #parseBeacons addressBookCallback returns public key


Instance 1:
# 94. #parseBeacons addressBookCallback returns public key


Instance 3:
# 94. #parseBeacons addressBookCallback returns public key


Instance 2:
ok 338 right number of calls to address book
ok 339 good preAmble
ok 340 good unencryptedKeyId
ok 341 good beacon
# teardown


Instance 3:
ok 339 right number of calls to address book
ok 340 good preAmble
ok 341 good unencryptedKeyId
ok 342 good beacon
# teardown


Instance 1:
ok 338 right number of calls to address book


Instance 1:
ok 339 good preAmble


Instance 1:
ok 340 good unencryptedKeyId


Instance 1:
ok 341 good beacon


Instance 1:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.276Z - info: Running on ios test: 95. validate generatePskIdentityField


Instance 2:
# 95. validate generatePskIdentityField


Instance 1:
# 95. validate generatePskIdentityField


Instance 3:
# 95. validate generatePskIdentityField


Instance 2:
ok 342 decoded buffers match


Instance 1:
ok 342 decoded buffers match
# teardown


Instance 2:
# teardown


Instance 3:
ok 343 decoded buffers match


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.293Z - info: Running on ios test: 96. validate generatePskSecret


Instance 2:
# 96. validate generatePskSecret


Instance 1:
# 96. validate generatePskSecret


Instance 3:
# 96. validate generatePskSecret


Instance 2:
ok 343 secrets match
# teardown


Instance 1:
ok 343 secrets match


Instance 1:
# teardown


Instance 3:
ok 344 secrets match


Instance 3:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.313Z - info: Running on ios test: 97. validate generatePskSecrets


Instance 2:
# 97. validate generatePskSecrets


Instance 1:
# 97. validate generatePskSecrets


Instance 3:
# 97. validate generatePskSecrets


Instance 1:
ok 344 Matching numbers
ok 345 We have an entry!
ok 346 keys match
ok 347 secrets match


Instance 2:
ok 344 Matching numbers
ok 345 We have an entry!
ok 346 keys match
ok 347 secrets match
ok 348 We have an entry!


Instance 2:
ok 349 keys match
ok 350 secrets match


Instance 1:
ok 348 We have an entry!
ok 349 keys match


Instance 1:
ok 350 secrets match


Instance 2:
ok 351 We have an entry!
ok 352 keys match
ok 353 secrets match


Instance 1:
ok 351 We have an entry!


Instance 2:
# teardown


Instance 1:
ok 352 keys match


Instance 1:
ok 353 secrets match


Instance 1:
# teardown


Instance 3:
ok 345 Matching numbers


Instance 3:
ok 346 We have an entry!


Instance 3:
ok 347 keys match


Instance 3:
ok 348 secrets match


Instance 3:
ok 349 We have an entry!


Instance 3:
ok 350 keys match


Instance 3:
ok 351 secrets match


Instance 3:
ok 352 We have an entry!


Instance 3:
ok 353 keys match


Instance 3:
ok 354 secrets match


Instance 3:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.351Z - info: Running on ios test: 98. validate generateBeaconStreamAndSecrets


Instance 1:
# 98. validate generateBeaconStreamAndSecrets


Instance 2:
# 98. validate generateBeaconStreamAndSecrets


Instance 3:
# 98. validate generateBeaconStreamAndSecrets


Instance 2:
ok 354 Streams have same length
ok 355 matching size
ok 356 keys match
ok 357 secrets match
# teardown


Instance 1:
ok 354 Streams have same length
ok 355 matching size
ok 356 keys match
ok 357 secrets match


Instance 3:
ok 355 Streams have same length
ok 356 matching size
ok 357 keys match
ok 358 secrets match
# teardown


Instance 1:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.386Z - info: Running on ios test: 99. Add two Peers.


Instance 2:
# 99. Add two Peers.


Instance 1:
# 99. Add two Peers.


Instance 3:
# 99. Add two Peers.


Instance 1:
_peerAvailabilityChanged


Instance 3:
_peerAvailabilityChanged


Instance 1:
peerIdentifier:id123
connectionType:AndroidBluetooth


Instance 1:
hostAddress:anything


Instance 3:
peerIdentifier:id123


Instance 1:
portNumber:8080


Instance 3:
connectionType:AndroidBluetooth
hostAddress:anything


Instance 3:
portNumber:8080
_peerAvailabilityChanged - end


Instance 1:
_peerAvailabilityChanged - end


Instance 3:
ok 359 should be equal


Instance 3:
_peerAvailabilityChanged


Instance 3:
peerIdentifier:id3212


Instance 3:
connectionType:tcp
hostAddress:anything
portNumber:8080


Instance 3:
_peerAvailabilityChanged - end


Instance 1:
ok 358 should be equal


Instance 1:
_peerAvailabilityChanged


Instance 1:
peerIdentifier:id3212


Instance 1:
connectionType:tcp


Instance 1:
hostAddress:anything


Instance 1:
portNumber:8080


Instance 1:
_peerAvailabilityChanged - end


Instance 3:
ok 360 should be equal


Instance 1:
ok 359 should be equal


Instance 3:
ok 361 should be equal


Instance 3:
ok 362 should be equal


Instance 3:
ok 363 should be equal


Instance 1:
ok 360 should be equal


Instance 1:
ok 361 should be equal


Instance 3:
# teardown


Instance 1:
ok 362 should be equal


Instance 1:
# teardown


Instance 2:
_peerAvailabilityChanged


Instance 2:
peerIdentifier:id123


Instance 2:
connectionType:AndroidBluetooth
hostAddress:anything


Instance 2:
portNumber:8080


Instance 2:
_peerAvailabilityChanged - end


Instance 2:
ok 358 should be equal
_peerAvailabilityChanged
peerIdentifier:id3212


Instance 2:
connectionType:tcp
hostAddress:anything
portNumber:8080


Instance 2:
_peerAvailabilityChanged - end


Instance 2:
ok 359 should be equal


Instance 2:
ok 360 should be equal


Instance 2:
ok 361 should be equal


Instance 2:
ok 362 should be equal


Instance 2:
# teardown


Instance 1:
killed


Instance 1:
# setup


Instance 2:
killed


Instance 3:
killed


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.432Z - info: Running on ios test: 100. TCP_NATIVE peer loses DNS


Instance 1:
# 100. TCP_NATIVE peer loses DNS


Instance 3:
# 100. TCP_NATIVE peer loses DNS


Instance 2:
# 100. TCP_NATIVE peer loses DNS


Instance 3:
_peerAvailabilityChanged


Instance 1:
_peerAvailabilityChanged


Instance 3:
peerIdentifier:id124


Instance 3:
connectionType:tcp


Instance 3:
hostAddress:127.0.0.1


Instance 1:
peerIdentifier:id124


Instance 3:
portNumber:50864


Instance 3:
_peerAvailabilityChanged - end


Instance 2:
_peerAvailabilityChanged


Instance 1:
connectionType:tcp
hostAddress:127.0.0.1


Instance 1:
portNumber:50863


Instance 1:
_peerAvailabilityChanged - end


Instance 2:
peerIdentifier:id124


Instance 2:
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50865


Instance 3:
ok 364 should be equal


Instance 3:
_peerAvailabilityChanged


Instance 3:
peerIdentifier:id124
connectionType:tcp


Instance 3:
hostAddress:undefined


Instance 3:
portNumber:50864


Instance 3:
_peerAvailabilityChanged - end


Instance 2:
_peerAvailabilityChanged - end


Instance 3:
ok 365 should be equal


Instance 1:
ok 363 should be equal


Instance 1:
_peerAvailabilityChanged


Instance 1:
peerIdentifier:id124


Instance 1:
connectionType:tcp


Instance 3:
# teardown


Instance 1:
hostAddress:undefined


Instance 1:
portNumber:50863


Instance 1:
_peerAvailabilityChanged - end


Instance 1:
ok 364 should be equal


Instance 1:
# teardown


Instance 2:
ok 363 should be equal


Instance 2:
_peerAvailabilityChanged


Instance 2:
peerIdentifier:id124


Instance 2:
connectionType:tcp


Instance 2:
hostAddress:undefined


Instance 2:
portNumber:50865


Instance 2:
_peerAvailabilityChanged - end


Instance 2:
ok 364 should be equal


Instance 2:
# teardown


Instance 1:
killed


Instance 1:
# setup


Instance 2:
killed


Instance 3:
killed


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:08:55.471Z - info: Running on ios test: 101. Resolves an action locally


Instance 1:
# 101. Resolves an action locally


Instance 2:
# 101. Resolves an action locally


Instance 3:
# 101. Resolves an action locally


Instance 3:
_peerAvailabilityChanged
peerIdentifier:id124


Instance 1:
_peerAvailabilityChanged


Instance 3:
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50868
_peerAvailabilityChanged - end


Instance 1:
peerIdentifier:id124


Instance 1:
connectionType:tcp


Instance 1:
hostAddress:127.0.0.1


Instance 1:
portNumber:50866
_peerAvailabilityChanged - end


Instance 2:
_peerAvailabilityChanged


Instance 2:
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1


Instance 2:
portNumber:50867


Instance 2:
_peerAvailabilityChanged - end


Instance 3:
ok 366 Host address must match


Instance 3:
ok 367 suggestedTCPTimeout must match


Instance 3:
ok 368 connectionType must match


Instance 3:
ok 369 portNumber must match


Instance 3:
# teardown


Instance 1:
ok 365 Host address must match


Instance 1:
ok 366 suggestedTCPTimeout must match


Instance 1:
ok 367 connectionType must match


Instance 1:
ok 368 portNumber must match


Instance 1:
# teardown


Instance 2:
ok 365 Host address must match


Instance 2:
ok 366 suggestedTCPTimeout must match


Instance 2:
ok 367 connectionType must match


Instance 2:
ok 368 portNumber must match


Instance 2:
# teardown


Instance 3:
killed


Instance 1:
killed


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
killed


Instance 2:
# setup


2016-03-29T08:08:55.520Z - info: Running on ios test: 102. Resolves an action locally using ThaliPeerPoolDefault


Instance 1:
# 102. Resolves an action locally using ThaliPeerPoolDefault


Instance 3:
# 102. Resolves an action locally using ThaliPeerPoolDefault


Instance 2:
# 102. Resolves an action locally using ThaliPeerPoolDefault


Instance 2:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50874
_peerAvailabilityChanged - end


Instance 1:
_peerAvailabilityChanged


Instance 1:
peerIdentifier:id124
connectionType:tcp


Instance 1:
hostAddress:127.0.0.1


Instance 1:
portNumber:50872


Instance 1:
_peerAvailabilityChanged - end


Instance 3:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50873
_peerAvailabilityChanged - end


Instance 2:
ok 369 Host address must match
ok 370 suggestedTCPTimeout must match
ok 371 connectionType must match


Instance 2:
ok 372 portNumber must match


Instance 2:
# teardown


Instance 1:
ok 369 Host address must match
ok 370 suggestedTCPTimeout must match
ok 371 connectionType must match
ok 372 portNumber must match


Instance 1:
# teardown


Instance 3:
ok 370 Host address must match


Instance 3:
ok 371 suggestedTCPTimeout must match


Instance 3:
ok 372 connectionType must match


Instance 3:
ok 373 portNumber must match


Instance 3:
# teardown


Instance 2:
killed


Instance 2:
# setup


Instance 1:
killed


Instance 1:
# setup


Instance 3:
killed


Instance 3:
# setup


2016-03-29T08:08:55.563Z - info: Running on ios test: 103. Action fails because of a bad hostname.


Instance 2:
# 103. Action fails because of a bad hostname.


Instance 1:
# 103. Action fails because of a bad hostname.


Instance 3:
# 103. Action fails because of a bad hostname.


Instance 2:
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:tcp
hostAddress:address-that-does-not-exists
portNumber:123
_peerAvailabilityChanged - end


Instance 3:
_peerAvailabilityChanged


Instance 3:
peerIdentifier:id123
connectionType:tcp
hostAddress:address-that-does-not-exists


Instance 3:
portNumber:123
_peerAvailabilityChanged - end


Instance 1:
_peerAvailabilityChanged
peerIdentifier:id123
connectionType:tcp
hostAddress:address-that-does-not-exists


Instance 1:
portNumber:123
_peerAvailabilityChanged - end


Instance 2:
ok 373 should be equal
ok 374 should be equal
ok 375 should be equal
# teardown


Instance 3:
ok 374 should be equal
ok 375 should be equal
ok 376 should be equal
# teardown


Instance 1:
ok 373 should be equal
ok 374 should be equal
ok 375 should be equal
# teardown


Instance 1:
killed


Instance 1:
# setup


Instance 3:
killed
# setup


Instance 2:
killed
# setup


2016-03-29T08:09:00.610Z - info: Running on ios test: 104. hostaddress is removed when the action is running. 


Instance 1:
# 104. hostaddress is removed when the action is running. 


Instance 2:
# 104. hostaddress is removed when the action is running. 


Instance 3:
# 104. hostaddress is removed when the action is running. 


Instance 1:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50881
_peerAvailabilityChanged - end


Instance 3:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50883
_peerAvailabilityChanged - end


Instance 2:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:127.0.0.1
portNumber:50882
_peerAvailabilityChanged - end


Instance 1:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:undefined
portNumber:50881
_peerAvailabilityChanged - end
ok 376 should be equal


Instance 3:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:undefined
portNumber:50883
_peerAvailabilityChanged - end
ok 377 should be equal


Instance 2:
_peerAvailabilityChanged
peerIdentifier:id124
connectionType:tcp
hostAddress:undefined
portNumber:50882
_peerAvailabilityChanged - end


Instance 3:
# teardown


Instance 2:
ok 376 should be equal


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
killed
# setup


Instance 2:
killed
# setup


Instance 3:
killed
# setup


2016-03-29T08:09:02.653Z - info: Running on ios test: 105. Start and stop ThaliNotificationServer


Instance 3:
# 105. Start and stop ThaliNotificationServer


Instance 1:
# 105. Start and stop ThaliNotificationServer


Instance 2:
# 105. Start and stop ThaliNotificationServer


Instance 2:
ok 377 ThaliMobile.StartUpdateAdvertisingAndListening should be called once


Instance 2:
ok 378 ThaliMobile.StopAdvertisingAndListeningshould be called once


Instance 2:
# teardown


Instance 3:
ok 378 ThaliMobile.StartUpdateAdvertisingAndListening should be called once


Instance 3:
ok 379 ThaliMobile.StopAdvertisingAndListeningshould be called once


Instance 3:
# teardown


Instance 1:
ok 377 ThaliMobile.StartUpdateAdvertisingAndListening should be called once


Instance 1:
ok 378 ThaliMobile.StopAdvertisingAndListeningshould be called once


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:02.689Z - info: Running on ios test: 106. Pass an empty array to ThaliNotificationServer.start


Instance 2:
# 106. Pass an empty array to ThaliNotificationServer.start


Instance 3:
# 106. Pass an empty array to ThaliNotificationServer.start


Instance 1:
# 106. Pass an empty array to ThaliNotificationServer.start


Instance 2:
ok 379 StartUpdateAdvertisingAndListening should not be called


Instance 3:
ok 380 StartUpdateAdvertisingAndListening should not be called


Instance 2:
ok 380 ThaliMobile.StopAdvertisingAndListening should be called once


Instance 3:
ok 381 ThaliMobile.StopAdvertisingAndListening should be called once


Instance 1:
ok 379 StartUpdateAdvertisingAndListening should not be called


Instance 1:
ok 380 ThaliMobile.StopAdvertisingAndListening should be called once


Instance 3:
ok 382 no error


Instance 3:
ok 383 should be 204


Instance 3:
# teardown


Instance 2:
ok 381 no error


Instance 2:
ok 382 should be 204


Instance 2:
# teardown


Instance 1:
ok 381 no error


Instance 1:
ok 382 should be 204


Instance 1:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:09:02.736Z - info: Running on ios test: 107. Pass a string to ThaliNotificationServer.start


Instance 3:
# 107. Pass a string to ThaliNotificationServer.start


Instance 1:
# 107. Pass a string to ThaliNotificationServer.start


Instance 2:
# 107. Pass a string to ThaliNotificationServer.start


Instance 3:
ok 384 StartUpdateAdvertisingAndListening should not be called


Instance 3:
# teardown


Instance 1:
ok 383 StartUpdateAdvertisingAndListening should not be called


Instance 1:
# teardown


Instance 2:
ok 383 StartUpdateAdvertisingAndListening should not be called


Instance 2:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:02.765Z - info: Running on ios test: 108. Pass an empty parameter to ThaliNotificationServer.start


Instance 3:
# 108. Pass an empty parameter to ThaliNotificationServer.start


Instance 2:
# 108. Pass an empty parameter to ThaliNotificationServer.start


Instance 1:
# 108. Pass an empty parameter to ThaliNotificationServer.start


Instance 3:
ok 385 StartUpdateAdvertisingAndListening should not be called
# teardown


Instance 2:
ok 384 StartUpdateAdvertisingAndListening should not be called
# teardown


Instance 1:
ok 384 StartUpdateAdvertisingAndListening should not be called


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:02.793Z - info: Running on ios test: 109. Make an HTTP request to /NotificationBeacons


Instance 2:
# 109. Make an HTTP request to /NotificationBeacons


Instance 3:
# 109. Make an HTTP request to /NotificationBeacons


Instance 1:
# 109. Make an HTTP request to /NotificationBeacons


Instance 3:
ok 386 no error


Instance 2:
ok 385 no error


Instance 3:
ok 387 should be 200


Instance 3:
ok 388 should be equal


Instance 2:
ok 386 should be 200


Instance 3:
ok 389 should be equal


Instance 2:
ok 387 should be equal


Instance 2:
ok 388 should be equal


Instance 3:
ok 390 (unnamed assert)


Instance 2:
ok 389 (unnamed assert)


Instance 2:
ok 390 no error


Instance 2:
ok 391 should be 204


Instance 3:
ok 391 no error


Instance 3:
ok 392 should be 204


Instance 2:
# teardown


Instance 3:
# teardown


Instance 1:
ok 385 no error


Instance 1:
ok 386 should be 200


Instance 1:
ok 387 should be equal


Instance 1:
ok 388 should be equal


Instance 1:
ok 389 (unnamed assert)


Instance 1:
ok 390 no error


Instance 1:
ok 391 should be 204


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:09:02.852Z - info: Running on ios test: 110. Make an HTTP request to /NotificationBeacons (no keys)


Instance 2:
# 110. Make an HTTP request to /NotificationBeacons (no keys)


Instance 3:
# 110. Make an HTTP request to /NotificationBeacons (no keys)


Instance 1:
# 110. Make an HTTP request to /NotificationBeacons (no keys)


Instance 2:
ok 392 error should be null


Instance 2:
ok 393 should be 204


Instance 3:
ok 393 error should be null


Instance 3:
ok 394 should be 204


Instance 2:
# teardown


Instance 3:
# teardown


Instance 1:
ok 392 error should be null


Instance 1:
ok 393 should be 204


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:02.885Z - info: Running on ios test: 111. Make an HTTP request to /NotificationBeaconsbefore calling start


Instance 3:
# 111. Make an HTTP request to /NotificationBeaconsbefore calling start


Instance 2:
# 111. Make an HTTP request to /NotificationBeaconsbefore calling start


Instance 1:
# 111. Make an HTTP request to /NotificationBeaconsbefore calling start


Instance 3:
ok 395 should be 404


Instance 3:
# teardown


Instance 2:
ok 394 should be 404


Instance 2:
# teardown


Instance 1:
ok 394 should be 404


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:02.920Z - info: Running on ios test: 112. #testThaliPeerAction - test getters


Instance 2:
# 112. #testThaliPeerAction - test getters


Instance 1:
# 112. #testThaliPeerAction - test getters


Instance 3:
# 112. #testThaliPeerAction - test getters


Instance 3:
ok 396 getPeerIdentifier


Instance 3:
ok 397 getConnectionType


Instance 3:
ok 398 getActionType


Instance 1:
ok 395 getPeerIdentifier


Instance 3:
ok 399 getActionState


Instance 1:
ok 396 getConnectionType


Instance 3:
# teardown


Instance 1:
ok 397 getActionType


Instance 1:
ok 398 getActionState


Instance 1:
# teardown


Instance 2:
ok 395 getPeerIdentifier


Instance 2:
ok 396 getConnectionType


Instance 2:
ok 397 getActionType


Instance 2:
ok 398 getActionState


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:02.944Z - info: Running on ios test: 113. #testThaliPeerAction - start and kill


Instance 1:
# 113. #testThaliPeerAction - start and kill


Instance 3:
# 113. #testThaliPeerAction - start and kill


Instance 2:
# 113. #testThaliPeerAction - start and kill


Instance 3:
ok 400 initial state


Instance 3:
ok 401 after start


Instance 3:
ok 402 after kill


Instance 3:
# teardown


Instance 2:
ok 399 initial state


Instance 1:
ok 399 initial state


Instance 2:
ok 400 after start


Instance 1:
ok 400 after start


Instance 1:
ok 401 after kill


Instance 2:
ok 401 after kill


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:02.970Z - info: Running on ios test: 114. #testThaliPeerAction - double start


Instance 3:
# 114. #testThaliPeerAction - double start


Instance 2:
# 114. #testThaliPeerAction - double start


Instance 1:
# 114. #testThaliPeerAction - double start


Instance 1:
ok 402 should be equal


Instance 1:
# teardown


Instance 2:
ok 402 should be equal


Instance 2:
# teardown


Instance 3:
ok 403 should be equal


Instance 3:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:09:02.996Z - info: Running on ios test: 115. #testThaliPeerAction - start after kill


Instance 3:
# 115. #testThaliPeerAction - start after kill


Instance 1:
# 115. #testThaliPeerAction - start after kill


Instance 2:
# 115. #testThaliPeerAction - start after kill


Instance 1:
ok 403 clean kill


Instance 3:
ok 404 clean kill


Instance 1:
ok 404 should be equal


Instance 1:
# teardown


Instance 3:
ok 405 should be equal


Instance 3:
# teardown


Instance 2:
ok 403 clean kill


Instance 2:
ok 404 should be equal


Instance 2:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:09:03.016Z - info: Running on ios test: 116. #testThaliPeerAction - make sure ids are unique


Instance 1:
# 116. #testThaliPeerAction - make sure ids are unique


Instance 3:
# 116. #testThaliPeerAction - make sure ids are unique


Instance 2:
# 116. #testThaliPeerAction - make sure ids are unique


Instance 3:
ok 406 should not be equal


Instance 1:
ok 405 should not be equal


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
ok 405 should not be equal


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:03.033Z - info: Running on ios test: 117. Test PeerConnectionInformation basics


Instance 3:
# 117. Test PeerConnectionInformation basics


Instance 2:
# 117. Test PeerConnectionInformation basics


Instance 1:
# 117. Test PeerConnectionInformation basics


Instance 1:
ok 406 connection type works
ok 407 getHostAddress works
ok 408 getPortNumber works
ok 409 getSuggestedTCPTimeout works
# teardown


Instance 2:
ok 406 connection type works
ok 407 getHostAddress works
ok 408 getPortNumber works
ok 409 getSuggestedTCPTimeout works


Instance 3:
ok 407 connection type works


Instance 3:
ok 408 getHostAddress works


Instance 2:
# teardown


Instance 3:
ok 409 getPortNumber works


Instance 3:
ok 410 getSuggestedTCPTimeout works


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:03.052Z - info: Running on ios test: 118. Test PeerDictionary basic functionality


Instance 1:
# 118. Test PeerDictionary basic functionality


Instance 3:
# 118. Test PeerDictionary basic functionality


Instance 2:
# 118. Test PeerDictionary basic functionality


Instance 3:
ok 411 Entry counter must be 1
ok 412 Size must be 1
ok 413 Entry counter must be 2
ok 414 Size must be 2
ok 415 Entry2 should not be found
ok 416 Size must be 1
ok 417 Size must be 0
# teardown


Instance 2:
ok 410 Entry counter must be 1
ok 411 Size must be 1
ok 412 Entry counter must be 2
ok 413 Size must be 2


Instance 1:
ok 410 Entry counter must be 1
ok 411 Size must be 1


Instance 1:
ok 412 Entry counter must be 2
ok 413 Size must be 2


Instance 2:
ok 414 Entry2 should not be found
ok 415 Size must be 1
ok 416 Size must be 0


Instance 1:
ok 414 Entry2 should not be found


Instance 1:
ok 415 Size must be 1
ok 416 Size must be 0


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:03.072Z - info: Running on ios test: 119. Test PeerDictionary with multiple entries.


Instance 1:
# 119. Test PeerDictionary with multiple entries.


Instance 3:
# 119. Test PeerDictionary with multiple entries.


Instance 2:
# 119. Test PeerDictionary with multiple entries.


Instance 2:
ok 417 Size must be100
ok 418 Entries between 20 and MAXSIZE + 20 should exist


Instance 1:
ok 417 Size must be100
ok 418 Entries between 20 and MAXSIZE + 20 should exist


Instance 3:
ok 418 Size must be100
ok 419 Entries between 20 and MAXSIZE + 20 should exist


Instance 2:
ok 419 WAITING state entry should not be removed
# teardown


Instance 3:
ok 420 WAITING state entry should not be removed


Instance 3:
# teardown


Instance 1:
ok 419 WAITING state entry should not be removed


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.277Z - info: Running on ios test: 120. RESOLVED entries are removed before WAITING state entry.


Instance 3:
# 120. RESOLVED entries are removed before WAITING state entry.


Instance 2:
# 120. RESOLVED entries are removed before WAITING state entry.


Instance 1:
# 120. RESOLVED entries are removed before WAITING state entry.


Instance 1:
ok 420 Entries between 6 and MAXSIZE + 4 should exist


Instance 1:
ok 421 Size should be MAXSIZE


Instance 2:
ok 420 Entries between 6 and MAXSIZE + 4 should exist


Instance 2:
ok 421 Size should be MAXSIZE


Instance 1:
ok 422 Size should be MAXSIZE+6


Instance 2:
ok 422 Size should be MAXSIZE+6


Instance 2:
# teardown


Instance 3:
ok 421 Entries between 6 and MAXSIZE + 4 should exist


Instance 3:
ok 422 Size should be MAXSIZE


Instance 3:
ok 423 Size should be MAXSIZE+6


Instance 1:
# teardown


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:03.379Z - info: Running on ios test: 121. WAITING entries are removed before CONTROLLED_BY_POOL state entry.


Instance 1:
# 121. WAITING entries are removed before CONTROLLED_BY_POOL state entry.


Instance 2:
# 121. WAITING entries are removed before CONTROLLED_BY_POOL state entry.


Instance 3:
# 121. WAITING entries are removed before CONTROLLED_BY_POOL state entry.


Instance 2:
ok 423 WAITING state entry should not be removed


Instance 2:
ok 424 Waiting entries between 6 and MAXSIZE + 4 should exist


Instance 2:
ok 425 Size should be MAXSIZE


Instance 2:
ok 426 entryCounter should be MAXSIZE+6


Instance 2:
# teardown


Instance 3:
ok 424 WAITING state entry should not be removed


Instance 3:
ok 425 Waiting entries between 6 and MAXSIZE + 4 should exist


Instance 3:
ok 426 Size should be MAXSIZE


Instance 3:
ok 427 entryCounter should be MAXSIZE+6


Instance 3:
# teardown


Instance 1:
ok 423 WAITING state entry should not be removed


Instance 1:
ok 424 Waiting entries between 6 and MAXSIZE + 4 should exist


Instance 1:
ok 425 Size should be MAXSIZE


Instance 1:
ok 426 entryCounter should be MAXSIZE+6


Instance 1:
# teardown


Instance 2:
# setup


Instance 1:
# setup


Instance 3:
# setup


2016-03-29T08:09:03.479Z - info: Running on ios test: 122. When CONTROLLED_BY_POOL entry is removed and kill is called.


Instance 2:
# 122. When CONTROLLED_BY_POOL entry is removed and kill is called.


Instance 1:
# 122. When CONTROLLED_BY_POOL entry is removed and kill is called.


Instance 3:
# 122. When CONTROLLED_BY_POOL entry is removed and kill is called.


Instance 3:
ok 428 Kill should be called once
ok 429 Size should be 100
# teardown


Instance 1:
ok 427 Kill should be called once
ok 428 Size should be 100


Instance 1:
# teardown


Instance 2:
ok 427 Kill should be called once


Instance 2:
ok 428 Size should be 100


Instance 2:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.579Z - info: Running on ios test: 123. #ThaliPeerPoolInterface - bad enqueues


Instance 3:
# 123. #ThaliPeerPoolInterface - bad enqueues


Instance 2:
# 123. #ThaliPeerPoolInterface - bad enqueues


Instance 1:
# 123. #ThaliPeerPoolInterface - bad enqueues


Instance 3:
ok 430 null arg
ok 431 wrong arg type


Instance 3:
ok 432 wrong state


Instance 3:
# teardown


Instance 2:
ok 429 null arg
ok 430 wrong arg type
ok 431 wrong state


Instance 2:
# teardown


Instance 1:
ok 429 null arg


Instance 1:
ok 430 wrong arg type


Instance 1:
ok 431 wrong state


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.602Z - info: Running on ios test: 124. #ThaliPeerPoolInterface - do not allow same object type


Instance 3:
# 124. #ThaliPeerPoolInterface - do not allow same object type


Instance 2:
# 124. #ThaliPeerPoolInterface - do not allow same object type


Instance 1:
# 124. #ThaliPeerPoolInterface - do not allow same object type


Instance 3:
ok 433 good enqueue


Instance 3:
ok 434 should be equal


Instance 3:
# teardown


Instance 2:
ok 432 good enqueue
ok 433 should be equal
# teardown


Instance 1:
ok 432 good enqueue


Instance 1:
ok 433 should be equal


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:03.621Z - info: Running on ios test: 125. #ThaliPeerPoolInterface - make sure we catch kill and dequeue


Instance 3:
# 125. #ThaliPeerPoolInterface - make sure we catch kill and dequeue


Instance 2:
# 125. #ThaliPeerPoolInterface - make sure we catch kill and dequeue


Instance 1:
# 125. #ThaliPeerPoolInterface - make sure we catch kill and dequeue


Instance 3:
ok 435 good enqueue
ok 436 2nd good enqueue
ok 437 we are in the pool


Instance 3:
ok 438 We are out of the pool
ok 439 Action was killed
ok 440 The original kill was called too
ok 441 second item is still in queue
# teardown


Instance 1:
ok 434 good enqueue


Instance 1:
ok 435 2nd good enqueue
ok 436 we are in the pool


Instance 2:
ok 434 good enqueue
ok 435 2nd good enqueue
ok 436 we are in the pool


Instance 1:
ok 437 We are out of the pool
ok 438 Action was killed
ok 439 The original kill was called too
ok 440 second item is still in queue


Instance 2:
ok 437 We are out of the pool
ok 438 Action was killed
ok 439 The original kill was called too


Instance 2:
ok 440 second item is still in queue


Instance 1:
# teardown


Instance 2:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.641Z - info: Running on ios test: 126. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent


Instance 3:
# 126. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent


Instance 2:
# 126. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent


Instance 1:
# 126. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent


Instance 3:
ok 442 good enqueue
ok 443 first kill
ok 444 second NOOP kill


Instance 3:
# teardown


Instance 2:
ok 441 good enqueue


Instance 2:
ok 442 first kill
ok 443 second NOOP kill
# teardown


Instance 1:
ok 441 good enqueue


Instance 1:
ok 442 first kill


Instance 1:
ok 443 second NOOP kill


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.661Z - info: Running on ios test: 127. compareBufferArrays


Instance 3:
# 127. compareBufferArrays


Instance 2:
# 127. compareBufferArrays


Instance 1:
# 127. compareBufferArrays


Instance 3:
ok 445 should throw


Instance 2:
ok 444 should throw


Instance 2:
ok 445 should throw


Instance 3:
ok 446 should throw


Instance 3:
ok 447 (unnamed assert)


Instance 3:
ok 448 (unnamed assert)


Instance 2:
ok 446 (unnamed assert)


Instance 3:
ok 449 (unnamed assert)


Instance 3:
ok 450 (unnamed assert)


Instance 2:
ok 447 (unnamed assert)


Instance 2:
ok 448 (unnamed assert)


Instance 3:
ok 451 (unnamed assert)


Instance 2:
ok 449 (unnamed assert)


Instance 2:
ok 450 (unnamed assert)


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
ok 444 should throw


Instance 1:
ok 445 should throw


Instance 1:
ok 446 (unnamed assert)


Instance 1:
ok 447 (unnamed assert)


Instance 1:
ok 448 (unnamed assert)


Instance 1:
ok 449 (unnamed assert)


Instance 1:
ok 450 (unnamed assert)


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.685Z - info: Running on ios test: 128. Call start twice and get error


Instance 2:
# 128. Call start twice and get error


Instance 3:
# 128. Call start twice and get error


Instance 1:
# 128. Call start twice and get error


Instance 3:
ok 452 should throw


Instance 2:
ok 451 should throw


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
ok 451 should throw


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.703Z - info: Running on ios test: 129. Start and make sure it runs


Instance 1:
# 129. Start and make sure it runs


Instance 3:
# 129. Start and make sure it runs


Instance 2:
# 129. Start and make sure it runs


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.722Z - info: Running on ios test: 130. Make sure getTimeWhenRun is right after start


Instance 2:
# 130. Make sure getTimeWhenRun is right after start


Instance 3:
# 130. Make sure getTimeWhenRun is right after start


Instance 1:
# 130. Make sure getTimeWhenRun is right after start


Instance 3:
ok 453 (unnamed assert)


Instance 3:
# teardown


Instance 2:
ok 452 (unnamed assert)


Instance 1:
ok 452 (unnamed assert)


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.741Z - info: Running on ios test: 131. Make sure getTimeWhenRun is -1 after function is called


Instance 3:
# 131. Make sure getTimeWhenRun is -1 after function is called


Instance 2:
# 131. Make sure getTimeWhenRun is -1 after function is called


Instance 1:
# 131. Make sure getTimeWhenRun is -1 after function is called


Instance 3:
ok 454 should be equal


Instance 2:
ok 453 should be equal


Instance 2:
# teardown


Instance 3:
# teardown


Instance 1:
ok 453 should be equal


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.759Z - info: Running on ios test: 132. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running


Instance 3:
# 132. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running


Instance 2:
# 132. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running


Instance 1:
# 132. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running


Instance 2:
ok 454 should be equal


Instance 3:
ok 455 should be equal


Instance 3:
ok 456 should be equal


Instance 2:
ok 455 should be equal


Instance 3:
ok 457 should throw


Instance 2:
ok 456 should throw


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
ok 454 should be equal


Instance 1:
ok 455 should be equal


Instance 1:
ok 456 should throw


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.780Z - info: Running on ios test: 133. Test TransientState


Instance 3:
# 133. Test TransientState


Instance 2:
# 133. Test TransientState


Instance 1:
# 133. Test TransientState


Instance 3:
ok 458 should throw


Instance 2:
ok 457 should throw


Instance 3:
ok 459 should throw


Instance 3:
ok 460 should be equal


Instance 3:
ok 461 should be equal


Instance 3:
ok 462 should be equal


Instance 2:
ok 458 should throw


Instance 3:
ok 463 should be equal


Instance 2:
ok 459 should be equal


Instance 3:
ok 464 (unnamed assert)
ok 465 (unnamed assert)


Instance 3:
# teardown


Instance 2:
ok 460 should be equal
ok 461 should be equal
ok 462 should be equal


Instance 2:
ok 463 (unnamed assert)


Instance 2:
ok 464 (unnamed assert)


Instance 2:
# teardown


Instance 1:
ok 457 should throw


Instance 1:
ok 458 should throw


Instance 1:
ok 459 should be equal


Instance 1:
ok 460 should be equal


Instance 1:
ok 461 should be equal


Instance 1:
ok 462 should be equal


Instance 1:
ok 463 (unnamed assert)


Instance 1:
ok 464 (unnamed assert)


Instance 1:
# teardown


Instance 3:
# setup


Instance 1:
# setup


Instance 2:
# setup


2016-03-29T08:09:03.798Z - info: Running on ios test: 134. No peers and empty database


Instance 3:
# 134. No peers and empty database


Instance 2:
# 134. No peers and empty database


Instance 1:
# 134. No peers and empty database


Instance 3:
ok 466 verify failed
ok 467 constructor called once


Instance 3:
ok 468 constructor called with right args


Instance 3:
ok 469 match start arg


Instance 3:
ok 470 start called once


Instance 3:
ok 471 stop called once


Instance 3:
ok 472 stop after start


Instance 3:
# teardown


Instance 2:
ok 465 verify failed


Instance 2:
ok 466 constructor called once


Instance 2:
ok 467 constructor called with right args


Instance 2:
ok 468 match start arg


Instance 2:
ok 469 start called once


Instance 2:
ok 470 stop called once


Instance 2:
ok 471 stop after start


Instance 2:
# teardown


Instance 1:
ok 465 verify failed


Instance 1:
ok 466 constructor called once


Instance 1:
ok 467 constructor called with right args


Instance 1:
ok 468 match start arg


Instance 1:
ok 469 start called once
ok 470 stop called once


Instance 1:
ok 471 stop after start


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.860Z - info: Running on ios test: 135. One peer and empty DB


Instance 3:
# 135. One peer and empty DB


Instance 2:
# 135. One peer and empty DB


Instance 1:
# 135. One peer and empty DB


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 473 verify failed


Instance 3:
ok 474 constructor called once


Instance 3:
ok 475 constructor called with right args


Instance 3:
ok 476 match start arg


Instance 3:
ok 477 start called once
ok 478 stop called once
ok 479 stop after start


Instance 3:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 472 verify failed


Instance 2:
ok 473 constructor called once


Instance 2:
ok 474 constructor called with right args


Instance 2:
ok 475 match start arg


Instance 2:
ok 476 start called once


Instance 2:
ok 477 stop called once


Instance 2:
ok 478 stop after start


Instance 2:
# teardown


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 472 verify failed


Instance 1:
ok 473 constructor called once


Instance 1:
ok 474 constructor called with right args


Instance 1:
ok 475 match start arg


Instance 1:
ok 476 start called once


Instance 1:
ok 477 stop called once


Instance 1:
ok 478 stop after start


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.922Z - info: Running on ios test: 136. One peer with _Local set behind current seq


Instance 3:
# 136. One peer with _Local set behind current seq


Instance 2:
# 136. One peer with _Local set behind current seq


Instance 1:
# 136. One peer with _Local set behind current seq


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 479 verify failed


Instance 2:
ok 480 constructor called once


Instance 2:
ok 481 constructor called with right args


Instance 2:
ok 482 match start arg


Instance 2:
ok 483 start called once


Instance 2:
ok 484 stop called once


Instance 2:
ok 485 stop after start


Instance 2:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 480 verify failed


Instance 3:
ok 481 constructor called once


Instance 3:
ok 482 constructor called with right args


Instance 3:
ok 483 match start arg


Instance 3:
ok 484 start called once


Instance 3:
ok 485 stop called once


Instance 3:
ok 486 stop after start


Instance 3:
# teardown


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 479 verify failed


Instance 1:
ok 480 constructor called once


Instance 1:
ok 481 constructor called with right args


Instance 1:
ok 482 match start arg


Instance 1:
ok 483 start called once


Instance 1:
ok 484 stop called once


Instance 1:
ok 485 stop after start


Instance 1:
# teardown


Instance 2:
# setup


Instance 3:
# setup


Instance 1:
# setup


2016-03-29T08:09:03.995Z - info: Running on ios test: 137. One peer with _Local set equal to current seq


Instance 3:
# 137. One peer with _Local set equal to current seq


Instance 2:
# 137. One peer with _Local set equal to current seq


Instance 1:
# 137. One peer with _Local set equal to current seq


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 486 verify failed


Instance 2:
ok 487 constructor called once


Instance 2:
ok 488 constructor called with right args


Instance 2:
ok 489 match start arg


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 490 start called once


Instance 2:
ok 491 stop called once


Instance 2:
ok 492 stop after start


Instance 3:
ok 487 verify failed


Instance 3:
ok 488 constructor called once


Instance 2:
# teardown


Instance 3:
ok 489 constructor called with right args


Instance 3:
ok 490 match start arg


Instance 3:
ok 491 start called once


Instance 3:
ok 492 stop called once


Instance 3:
ok 493 stop after start


Instance 3:
# teardown


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 486 verify failed


Instance 1:
ok 487 constructor called once


Instance 1:
ok 488 constructor called with right args


Instance 1:
ok 489 match start arg


Instance 1:
ok 490 start called once


Instance 1:
ok 491 stop called once


Instance 1:
ok 492 stop after start


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:04.050Z - info: Running on ios test: 138. One peer with _Local set ahead of current seq (and no this should not happen)


Instance 2:
# 138. One peer with _Local set ahead of current seq (and no this should not happen)


Instance 3:
# 138. One peer with _Local set ahead of current seq (and no this should not happen)


Instance 1:
# 138. One peer with _Local set ahead of current seq (and no this should not happen)


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 493 verify failed


Instance 2:
ok 494 constructor called once


Instance 2:
ok 495 constructor called with right args


Instance 2:
ok 496 match start arg


Instance 2:
ok 497 start called once


Instance 2:
ok 498 stop called once


Instance 2:
ok 499 stop after start


Instance 2:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 494 verify failed


Instance 3:
ok 495 constructor called once


Instance 3:
ok 496 constructor called with right args


Instance 3:
ok 497 match start arg


Instance 3:
ok 498 start called once


Instance 3:
ok 499 stop called once


Instance 3:
ok 500 stop after start


Instance 3:
# teardown


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 493 verify failed


Instance 1:
ok 494 constructor called once


Instance 1:
ok 495 constructor called with right args


Instance 1:
ok 496 match start arg


Instance 1:
ok 497 start called once


Instance 1:
ok 498 stop called once


Instance 1:
ok 499 stop after start


Instance 1:
# teardown


Instance 3:
# setup


Instance 2:
# setup


Instance 1:
# setup


2016-03-29T08:09:04.105Z - info: Running on ios test: 139. Three peers, one not in DB, one behind and one ahead


Instance 3:
# 139. Three peers, one not in DB, one behind and one ahead


Instance 2:
# 139. Three peers, one not in DB, one behind and one ahead


Instance 1:
# 139. Three peers, one not in DB, one behind and one ahead


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 500 verify failed


Instance 2:
ok 501 constructor called once


Instance 2:
ok 502 constructor called with right args


Instance 2:
ok 503 match start arg


Instance 2:
ok 504 start called once


Instance 2:
ok 505 stop called once


Instance 2:
ok 506 stop after start


Instance 2:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 501 verify failed


Instance 3:
ok 502 constructor called once


Instance 3:
ok 503 constructor called with right args


Instance 3:
ok 504 match start arg


Instance 3:
ok 505 start called once


Instance 3:
ok 506 stop called once


Instance 3:
ok 507 stop after start


Instance 3:
# teardown


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 500 verify failed


Instance 1:
ok 501 constructor called once


Instance 1:
ok 502 constructor called with right args


Instance 1:
ok 503 match start arg


Instance 1:
ok 504 start called once


Instance 1:
ok 505 stop called once


Instance 1:
ok 506 stop after start


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:04.175Z - info: Running on ios test: 140. More than maximum peers, make sure we only send maximum allowed


Instance 3:
# 140. More than maximum peers, make sure we only send maximum allowed


Instance 1:
# 140. More than maximum peers, make sure we only send maximum allowed


Instance 2:
# 140. More than maximum peers, make sure we only send maximum allowed


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 508 verify failed


Instance 3:
ok 509 constructor called once


Instance 3:
ok 510 constructor called with right args


Instance 3:
ok 511 match start arg


Instance 3:
ok 512 start called once


Instance 3:
ok 513 stop called once


Instance 3:
ok 514 stop after start


Instance 3:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 507 verify failed


Instance 2:
ok 508 constructor called once
ok 509 constructor called with right args


Instance 2:
ok 510 match start arg
ok 511 start called once


Instance 2:
ok 512 stop called once
ok 513 stop after start


Instance 2:
# teardown


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 507 verify failed


Instance 1:
ok 508 constructor called once


Instance 1:
ok 509 constructor called with right args


Instance 1:
ok 510 match start arg
ok 511 start called once


Instance 1:
ok 512 stop called once
ok 513 stop after start


Instance 1:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:04.298Z - info: Running on ios test: 141. two peers with empty DB, update the doc


Instance 1:
# 141. two peers with empty DB, update the doc


Instance 3:
# 141. two peers with empty DB, update the doc


Instance 2:
# 141. two peers with empty DB, update the doc


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 514 verify failed


Instance 1:
ok 515 constructor called once


Instance 1:
ok 516 constructor called with right args


Instance 1:
ok 517 last start before stop
ok 518 empty first start
ok 519 full second start
ok 520 only 2 timers


Instance 1:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 514 verify failed


Instance 2:
ok 515 constructor called once


Instance 2:
ok 516 constructor called with right args


Instance 2:
ok 517 last start before stop


Instance 2:
ok 518 empty first start


Instance 2:
ok 519 full second start


Instance 2:
ok 520 only 2 timers


Instance 2:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 515 verify failed


Instance 3:
ok 516 constructor called once


Instance 3:
ok 517 constructor called with right args


Instance 3:
ok 518 last start before stop


Instance 3:
ok 519 empty first start


Instance 3:
ok 520 full second start


Instance 3:
ok 521 only 2 timers


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:04.420Z - info: Running on ios test: 142. add doc and make sure tokens refresh when they expire


Instance 3:
# 142. add doc and make sure tokens refresh when they expire


Instance 1:
# 142. add doc and make sure tokens refresh when they expire


Instance 2:
# 142. add doc and make sure tokens refresh when they expire


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 521 verify failed
ok 522 constructor called once
ok 523 constructor called with right args
ok 524 start before stop
ok 525 We got at least 3 calls to start
ok 526 at least 3
ok 527 default 1
ok 528 1 run
ok 529 default 2
ok 530 2 run
ok 531 default 3


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 521 verify failed
ok 522 constructor called once
ok 523 constructor called with right args
ok 524 start before stop
ok 525 We got at least 3 calls to start
ok 526 at least 3
ok 527 default 1
ok 528 1 run
ok 529 default 2
ok 530 2 run
ok 531 default 3
# teardown


Instance 1:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 522 verify failed


Instance 3:
ok 523 constructor called once


Instance 3:
ok 524 constructor called with right args


Instance 3:
ok 525 start before stop
ok 526 We got at least 3 calls to start
ok 527 at least 3
ok 528 default 1
ok 529 1 run


Instance 3:
ok 530 default 2


Instance 3:
ok 531 2 run


Instance 3:
ok 532 default 3


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:04.794Z - info: Running on ios test: 143. start and stop and start and stop


Instance 1:
# 143. start and stop and start and stop


Instance 2:
# 143. start and stop and start and stop


Instance 3:
# 143. start and stop and start and stop


Instance 1:
ok 532 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 533 back to null


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 534 still null
ok 535 verify failed
ok 536 constructor called once
ok 537 constructor called with right args
ok 538 first start before first stop
ok 539 first stop before second start
ok 540 second start before second stop
# teardown


Instance 2:
ok 532 start out null


Instance 3:
ok 533 start out null


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 533 back to null


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 534 back to null


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 534 still null


Instance 2:
ok 535 verify failed


Instance 2:
ok 536 constructor called once


Instance 2:
ok 537 constructor called with right args


Instance 2:
ok 538 first start before first stop


Instance 2:
ok 539 first stop before second start


Instance 2:
ok 540 second start before second stop


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
# teardown


Instance 3:
ok 535 still null


Instance 3:
ok 536 verify failed


Instance 3:
ok 537 constructor called once


Instance 3:
ok 538 constructor called with right args


Instance 3:
ok 539 first start before first stop


Instance 3:
ok 540 first stop before second start


Instance 3:
ok 541 second start before second stop


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:04.845Z - info: Running on ios test: 144. two identical starts in a row


Instance 1:
# 144. two identical starts in a row


Instance 2:
# 144. two identical starts in a row


Instance 3:
# 144. two identical starts in a row


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 541 verify failed


Instance 1:
ok 542 constructor called once


Instance 1:
ok 543 constructor called with right args


Instance 1:
ok 544 (unnamed assert)


Instance 1:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 541 verify failed


Instance 2:
ok 542 constructor called once


Instance 2:
ok 543 constructor called with right args


Instance 2:
ok 544 (unnamed assert)


Instance 2:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 542 verify failed


Instance 3:
ok 543 constructor called once


Instance 3:
ok 544 constructor called with right args


Instance 3:
ok 545 (unnamed assert)


Instance 3:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:04.892Z - info: Running on ios test: 145. two different starts in a row


Instance 1:
# 145. two different starts in a row


Instance 3:
# 145. two different starts in a row


Instance 2:
# 145. two different starts in a row


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 545 verify failed


Instance 1:
ok 546 constructor called once


Instance 1:
ok 547 constructor called with right args


Instance 1:
ok 548 (unnamed assert)


Instance 1:
ok 549 (unnamed assert)


Instance 1:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 546 verify failed


Instance 3:
ok 547 constructor called once


Instance 3:
ok 548 constructor called with right args


Instance 3:
ok 549 (unnamed assert)


Instance 3:
ok 550 (unnamed assert)


Instance 3:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 545 verify failed


Instance 2:
ok 546 constructor called once


Instance 2:
ok 547 constructor called with right args


Instance 2:
ok 548 (unnamed assert)


Instance 2:
ok 549 (unnamed assert)


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:04.946Z - info: Running on ios test: 146. two stops and a start and two stops


Instance 1:
# 146. two stops and a start and two stops


Instance 2:
# 146. two stops and a start and two stops


Instance 3:
# 146. two stops and a start and two stops


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 550 verify failed
ok 551 constructor called once
ok 552 constructor called with right args
ok 553 start before stop
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 551 verify failed
ok 552 constructor called once
ok 553 constructor called with right args
ok 554 start before stop


Instance 3:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 550 verify failed


Instance 2:
ok 551 constructor called once


Instance 2:
ok 552 constructor called with right args


Instance 2:
ok 553 start before stop


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:04.998Z - info: Running on ios test: 147. we properly enqueue requests so no then needed


Instance 1:
# 147. we properly enqueue requests so no then needed


Instance 2:
# 147. we properly enqueue requests so no then needed


Instance 3:
# 147. we properly enqueue requests so no then needed


Instance 1:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 1:
ok 554 verify failed
ok 555 constructor called once
ok 556 constructor called with right args
ok 557 start before stop


Instance 1:
# teardown


Instance 3:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 3:
ok 555 verify failed
ok 556 constructor called once
ok 557 constructor called with right args
ok 558 start before stop


Instance 3:
# teardown


Instance 2:
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}


Instance 2:
ok 554 verify failed


Instance 2:
ok 555 constructor called once


Instance 2:
ok 556 constructor called with right args


Instance 2:
ok 557 start before stop


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:05.046Z - info: Running on ios test: 148. test calculateSeqPointKeyId


Instance 1:
# 148. test calculateSeqPointKeyId


Instance 2:
# 148. test calculateSeqPointKeyId


Instance 3:
# 148. test calculateSeqPointKeyId


Instance 1:
ok 558 should be equal
ok 559 should be equal
# teardown


Instance 3:
ok 559 should be equal
ok 560 should be equal
# teardown


Instance 2:
ok 558 should be equal


Instance 2:
ok 559 should be equal


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.071Z - info: Running on ios test: 149. can create servers manager


Instance 1:
# 149. can create servers manager


Instance 3:
# 149. can create servers manager


Instance 2:
# 149. can create servers manager


Instance 1:
ok 560 serversManager must not be null
ok 561 serversManager must be an object


Instance 1:
# teardown


Instance 3:
ok 561 serversManager must not be null
ok 562 serversManager must be an object


Instance 3:
# teardown


Instance 2:
ok 560 serversManager must not be null


Instance 2:
ok 561 serversManager must be an object


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.090Z - info: Running on ios test: 150. calling stop without start causes error


Instance 1:
# 150. calling stop without start causes error


Instance 3:
# 150. calling stop without start causes error


Instance 2:
# 150. calling stop without start causes error


Instance 1:
ok 562 We need to call start first


Instance 1:
# teardown


Instance 3:
ok 563 We need to call start first
# teardown


Instance 2:
ok 562 We need to call start first


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.103Z - info: Running on ios test: 151. can start/stop servers manager


Instance 1:
# 151. can start/stop servers manager


Instance 2:
# 151. can start/stop servers manager


Instance 3:
# 151. can start/stop servers manager


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50923
ok 563 port must be in range
# teardown


Instance 3:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50924
ok 564 port must be in range


Instance 3:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50925


Instance 2:
ok 563 port must be in range


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.123Z - info: Running on ios test: 152. starting twice resolves with listening port


Instance 1:
# 152. starting twice resolves with listening port


Instance 3:
# 152. starting twice resolves with listening port


Instance 2:
# 152. starting twice resolves with listening port


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50926


Instance 1:
ok 564 second start should return same port


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50927
ok 565 second start should return same port
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50928


Instance 2:
ok 564 second start should return same port


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:05.144Z - info: Running on ios test: 153. terminateIncomingConnection will terminate a connection


Instance 1:
# 153. terminateIncomingConnection will terminate a connection


Instance 3:
# 153. terminateIncomingConnection will terminate a connection


Instance 2:
# 153. terminateIncomingConnection will terminate a connection


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50930


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 565 we should be connected


Instance 3:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: incoming socket close
ok 566 now we are disconnected


Instance 3:
DEBUG createNativeListener: listening 50933


Instance 1:
# teardown


Instance 3:
DEBUG createNativeListener: new incoming socket


Instance 3:
DEBUG createNativeListener: creating incoming mux


Instance 3:
DEBUG createNativeListener: new mux
ok 566 we should be connected


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50936


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 3:
DEBUG createNativeListener: incoming socket close
ok 567 now we are disconnected


Instance 2:
ok 565 we should be connected


Instance 3:
# teardown


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 566 now we are disconnected


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.172Z - info: Running on ios test: 154. terminate an Outgoing connection will terminate the server


Instance 1:
# 154. terminate an Outgoing connection will terminate the server


Instance 3:
# 154. terminate an Outgoing connection will terminate the server


Instance 2:
# 154. terminate an Outgoing connection will terminate the server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50938
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50939


Instance 3:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50940


Instance 2:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.191Z - info: Running on ios test: 155. terminate an Outgoing connection with wrong arguments is not harmful


Instance 1:
# 155. terminate an Outgoing connection with wrong arguments is not harmful


Instance 3:
# 155. terminate an Outgoing connection with wrong arguments is not harmful


Instance 2:
# 155. terminate an Outgoing connection with wrong arguments is not harmful


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50941
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50942
# teardown


Instance 3:
DEBUG createNativeListener: creating native server


Instance 3:
DEBUG createNativeListener: listening 50943


Instance 3:
# teardown


Instance 1:
# setup


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.208Z - info: Running on ios test: 156. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted


Instance 1:
ok 567 should be in started state
# 156. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted


Instance 3:
ok 568 should be in started state
# 156. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted


Instance 2:
ok 567 should be in started state


Instance 2:
# 156. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted


Instance 1:
ok 568 peer identifier should match
ok 569 host address should match
ok 570 port should match


Instance 1:
ok 571 host address should be null
ok 572 port should should be null
# teardown


Instance 3:
ok 569 peer identifier should match
ok 570 host address should match
ok 571 port should match


Instance 2:
ok 568 peer identifier should match
ok 569 host address should match
ok 570 port should match


Instance 3:
ok 572 host address should be null
ok 573 port should should be null


Instance 2:
ok 571 host address should be null
ok 572 port should should be null


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
ok 573 should not be in started state
# setup


Instance 3:
ok 574 should not be in started state


Instance 3:
# setup


Instance 2:
ok 573 should not be in started state
# setup


2016-03-29T08:09:05.232Z - info: Running on ios test: 157. #startUpdateAdvertisingAndListening should use different USN after every invocation


Instance 1:
ok 574 should be in started state


Instance 1:
# 157. #startUpdateAdvertisingAndListening should use different USN after every invocation


Instance 3:
ok 575 should be in started state
# 157. #startUpdateAdvertisingAndListening should use different USN after every invocation


Instance 2:
ok 574 should be in started state
# 157. #startUpdateAdvertisingAndListening should use different USN after every invocation


Instance 1:
ok 575 USN should have changed from the first one


Instance 1:
ok 576 when receiving the second byebye, the first USN should be already set


Instance 1:
# teardown


Instance 3:
ok 576 USN should have changed from the first one


Instance 3:
ok 577 when receiving the second byebye, the first USN should be already set


Instance 2:
ok 575 USN should have changed from the first one


Instance 3:
# teardown


Instance 2:
ok 576 when receiving the second byebye, the first USN should be already set


Instance 2:
# teardown


Instance 1:
ok 577 should not be in started state


Instance 1:
# setup


Instance 3:
ok 578 should not be in started state


Instance 3:
# setup


Instance 2:
ok 577 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.258Z - info: Running on ios test: 158. messages with invalid location or USN should be ignored


Instance 1:
ok 578 should be in started state
# 158. messages with invalid location or USN should be ignored


Instance 3:
ok 579 should be in started state


Instance 2:
ok 578 should be in started state


Instance 3:
# 158. messages with invalid location or USN should be ignored


Instance 2:
# 158. messages with invalid location or USN should be ignored


Instance 1:
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 579 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 580 should not have emitted with invalid USN
# teardown


Instance 3:
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000


Instance 3:
ok 580 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 581 should not have emitted with invalid USN
# teardown


Instance 2:
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 579 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 580 should not have emitted with invalid USN


Instance 2:
# teardown


Instance 1:
ok 581 should not be in started state
# setup


Instance 3:
ok 582 should not be in started state
# setup


Instance 2:
ok 581 should not be in started state
# setup


2016-03-29T08:09:05.278Z - info: Running on ios test: 159. verify that Thali-specific messages are filtered correctly


Instance 1:
ok 582 should be in started state


Instance 1:
# 159. verify that Thali-specific messages are filtered correctly


Instance 3:
ok 583 should be in started state


Instance 3:
# 159. verify that Thali-specific messages are filtered correctly


Instance 2:
ok 582 should be in started state


Instance 2:
# 159. verify that Thali-specific messages are filtered correctly


Instance 1:
ok 583 irrelevant messages should be ignored
ok 584 relevant messages should not be ignored


Instance 1:
ok 585 messages from this device should be ignored


Instance 1:
# teardown


Instance 3:
ok 584 irrelevant messages should be ignored


Instance 3:
ok 585 relevant messages should not be ignored


Instance 3:
ok 586 messages from this device should be ignored


Instance 3:
# teardown


Instance 2:
ok 583 irrelevant messages should be ignored


Instance 2:
ok 584 relevant messages should not be ignored


Instance 2:
ok 585 messages from this device should be ignored


Instance 2:
# teardown


Instance 1:
ok 586 should not be in started state
# setup


Instance 3:
ok 587 should not be in started state


Instance 3:
# setup


Instance 2:
ok 586 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.297Z - info: Running on ios test: 160. #startListeningForAdvertisements should fail if start not called


Instance 1:
ok 587 should be in started state
# 160. #startListeningForAdvertisements should fail if start not called


Instance 3:
ok 588 should be in started state


Instance 3:
# 160. #startListeningForAdvertisements should fail if start not called


Instance 2:
ok 587 should be in started state


Instance 2:
# 160. #startListeningForAdvertisements should fail if start not called


Instance 1:
ok 588 specific error should be returned
# teardown


Instance 3:
ok 589 specific error should be returned
# teardown


Instance 2:
ok 588 specific error should be returned
# teardown


Instance 1:
ok 589 should not be in started state
# setup


Instance 3:
ok 590 should not be in started state
# setup


Instance 2:
ok 589 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.316Z - info: Running on ios test: 161. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
ok 590 should be in started state


Instance 1:
# 161. #startUpdateAdvertisingAndListening should fail if start not called


Instance 2:
ok 590 should be in started state
# 161. #startUpdateAdvertisingAndListening should fail if start not called


Instance 3:
ok 591 should be in started state


Instance 3:
# 161. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
ok 591 specific error should be returned


Instance 1:
# teardown


Instance 2:
ok 591 specific error should be returned


Instance 2:
# teardown


Instance 3:
ok 592 specific error should be returned


Instance 3:
# teardown


Instance 2:
ok 592 should not be in started state


Instance 3:
ok 593 should not be in started state
# setup


Instance 2:
# setup


Instance 1:
ok 592 should not be in started state


Instance 1:
# setup


2016-03-29T08:09:05.331Z - info: Running on ios test: 162. #start should fail if called twice in a row


Instance 1:
ok 593 should be in started state
# 162. #start should fail if called twice in a row


Instance 3:
ok 594 should be in started state


Instance 3:
# 162. #start should fail if called twice in a row


Instance 2:
ok 593 should be in started state
# 162. #start should fail if called twice in a row


Instance 3:
ok 595 specific error should be received
# teardown


Instance 1:
ok 594 specific error should be received
# teardown


Instance 2:
ok 594 specific error should be received


Instance 2:
# teardown


Instance 3:
ok 596 should not be in started state
# setup


Instance 1:
ok 595 should not be in started state
# setup


Instance 2:
ok 595 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.350Z - info: Running on ios test: 163. should not be started after stop is called


Instance 1:
ok 596 should be in started state


Instance 1:
# 163. should not be started after stop is called


Instance 3:
ok 597 should be in started state


Instance 2:
ok 596 should be in started state


Instance 2:
# 163. should not be started after stop is called


Instance 3:
# 163. should not be started after stop is called


Instance 1:
ok 597 should not be started
ok 598 should not be listening


Instance 1:
ok 599 should not target listening


Instance 1:
ok 600 should not be advertising


Instance 1:
ok 601 should not target advertising


Instance 1:
# teardown


Instance 2:
ok 597 should not be started
ok 598 should not be listening


Instance 2:
ok 599 should not target listening


Instance 2:
ok 600 should not be advertising


Instance 2:
ok 601 should not target advertising


Instance 2:
# teardown


Instance 3:
ok 598 should not be started


Instance 3:
ok 599 should not be listening


Instance 3:
ok 600 should not target listening


Instance 3:
ok 601 should not be advertising


Instance 3:
ok 602 should not target advertising


Instance 3:
# teardown


Instance 1:
ok 602 should not be in started state


Instance 1:
# setup


Instance 2:
ok 602 should not be in started state


Instance 2:
# setup


Instance 3:
ok 603 should not be in started state


Instance 3:
# setup


2016-03-29T08:09:05.368Z - info: Running on ios test: 164. #startUpdateAdvertisingAndListening should fail invalid router has been passed


Instance 3:
ok 604 should be in started state
# 164. #startUpdateAdvertisingAndListening should fail invalid router has been passed


Instance 1:
ok 603 should be in started state


Instance 1:
# 164. #startUpdateAdvertisingAndListening should fail invalid router has been passed


Instance 2:
ok 603 should be in started state


Instance 2:
# 164. #startUpdateAdvertisingAndListening should fail invalid router has been passed


Instance 1:
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 604 specific error should be received
# teardown


Instance 3:
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 605 specific error should be received
# teardown


Instance 2:
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string


Instance 2:
ok 604 specific error should be received


Instance 2:
# teardown


Instance 1:
ok 605 should not be in started state


Instance 1:
# setup


Instance 3:
ok 606 should not be in started state


Instance 3:
# setup


Instance 2:
ok 605 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.387Z - info: Running on ios test: 165. #startUpdateAdvertisingAndListening should fail if router server starting fails


Instance 1:
ok 606 should be in started state
# 165. #startUpdateAdvertisingAndListening should fail if router server starting fails


Instance 3:
ok 607 should be in started state


Instance 3:
# 165. #startUpdateAdvertisingAndListening should fail if router server starting fails


Instance 2:
ok 606 should be in started state


Instance 2:
# 165. #startUpdateAdvertisingAndListening should fail if router server starting fails


Instance 3:
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 608 specific error expected
# teardown


Instance 1:
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 607 specific error expected
# teardown


Instance 2:
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 607 specific error expected


Instance 2:
# teardown


Instance 1:
ok 608 should not be in started state


Instance 1:
# setup


Instance 3:
ok 609 should not be in started state


Instance 3:
# setup


Instance 2:
ok 608 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.405Z - info: Running on ios test: 166. #startUpdateAdvertisingAndListening should start hosting given router object


Instance 3:
ok 610 should be in started state


Instance 1:
ok 609 should be in started state


Instance 3:
# 166. #startUpdateAdvertisingAndListening should start hosting given router object


Instance 1:
# 166. #startUpdateAdvertisingAndListening should start hosting given router object


Instance 2:
ok 609 should be in started state


Instance 2:
# 166. #startUpdateAdvertisingAndListening should start hosting given router object


Instance 1:
ok 610 server should respond with code 200


Instance 2:
ok 610 server should respond with code 200


Instance 1:
# teardown


Instance 2:
# teardown


Instance 3:
ok 611 server should respond with code 200


Instance 3:
# teardown


Instance 1:
ok 611 should not be in started state
# setup


Instance 3:
ok 612 should not be in started state


Instance 3:
# setup


Instance 2:
ok 611 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.448Z - info: Running on ios test: 167. #startUpdateAdvertisingAndListening bad psk should be rejected object


Instance 3:
ok 613 should be in started state
# 167. #startUpdateAdvertisingAndListening bad psk should be rejected object


Instance 1:
ok 612 should be in started state


Instance 1:
# 167. #startUpdateAdvertisingAndListening bad psk should be rejected object


Instance 2:
ok 612 should be in started state


Instance 2:
# 167. #startUpdateAdvertisingAndListening bad psk should be rejected object


Instance 1:
ok 613 Connection should be rejected


Instance 3:
ok 614 Connection should be rejected


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
ok 613 Connection should be rejected


Instance 2:
# teardown


Instance 1:
ok 614 should not be in started state


Instance 1:
# setup


Instance 3:
ok 615 should not be in started state


Instance 3:
# setup


Instance 2:
ok 614 should not be in started state


2016-03-29T08:09:05.484Z - info: Running on ios test: 168. #stop can be called multiple times in a row


Instance 2:
# setup


Instance 1:
ok 615 should be in started state


Instance 1:
# 168. #stop can be called multiple times in a row


Instance 3:
ok 616 should be in started state
# 168. #stop can be called multiple times in a row


Instance 2:
ok 615 should be in started state


Instance 2:
# 168. #stop can be called multiple times in a row


Instance 1:
ok 616 should be in stopped state
ok 617 should still be in stopped state
# teardown


Instance 3:
ok 617 should be in stopped state
ok 618 should still be in stopped state


Instance 3:
# teardown


Instance 2:
ok 616 should be in stopped state


Instance 2:
ok 617 should still be in stopped state


Instance 2:
# teardown


Instance 3:
ok 619 should not be in started state
# setup


Instance 1:
ok 618 should not be in started state


Instance 1:
# setup


Instance 2:
ok 618 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.500Z - info: Running on ios test: 169. #startListeningForAdvertisements can be called multiple times in a row


Instance 1:
ok 619 should be in started state
# 169. #startListeningForAdvertisements can be called multiple times in a row


Instance 3:
ok 620 should be in started state


Instance 2:
ok 619 should be in started state


Instance 3:
# 169. #startListeningForAdvertisements can be called multiple times in a row


Instance 2:
# 169. #startListeningForAdvertisements can be called multiple times in a row


Instance 1:
ok 620 should be in listening state
ok 621 should still be in listening state
# teardown


Instance 3:
ok 621 should be in listening state


Instance 3:
ok 622 should still be in listening state


Instance 3:
# teardown


Instance 2:
ok 620 should be in listening state


Instance 2:
ok 621 should still be in listening state


Instance 2:
# teardown


Instance 1:
ok 622 should not be in started state
# setup


Instance 3:
ok 623 should not be in started state


Instance 3:
# setup


Instance 2:
ok 622 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.520Z - info: Running on ios test: 170. #stopListeningForAdvertisements can be called multiple times in a row


Instance 1:
ok 623 should be in started state
# 170. #stopListeningForAdvertisements can be called multiple times in a row


Instance 3:
ok 624 should be in started state


Instance 3:
# 170. #stopListeningForAdvertisements can be called multiple times in a row


Instance 2:
ok 623 should be in started state


Instance 2:
# 170. #stopListeningForAdvertisements can be called multiple times in a row


Instance 1:
ok 624 should not be in listening state


Instance 1:
ok 625 should still not be in listening state


Instance 1:
# teardown


Instance 3:
ok 625 should not be in listening state


Instance 3:
ok 626 should still not be in listening state


Instance 3:
# teardown


Instance 2:
ok 624 should not be in listening state


Instance 2:
ok 625 should still not be in listening state


Instance 2:
# teardown


Instance 1:
ok 626 should not be in started state


Instance 1:
# setup


Instance 3:
ok 627 should not be in started state


Instance 3:
# setup


Instance 2:
ok 626 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.537Z - info: Running on ios test: 171. #stopAdvertisingAndListening can be called multiple times in a row


Instance 1:
ok 627 should be in started state


Instance 1:
# 171. #stopAdvertisingAndListening can be called multiple times in a row


Instance 3:
ok 628 should be in started state


Instance 3:
# 171. #stopAdvertisingAndListening can be called multiple times in a row


Instance 2:
ok 627 should be in started state


Instance 2:
# 171. #stopAdvertisingAndListening can be called multiple times in a row


Instance 3:
ok 629 should not be in advertising state
ok 630 should still not be in advertising state
# teardown


Instance 1:
ok 628 should not be in advertising state
ok 629 should still not be in advertising state
# teardown


Instance 2:
ok 628 should not be in advertising state


Instance 2:
ok 629 should still not be in advertising state


Instance 2:
# teardown


Instance 3:
ok 631 should not be in started state
# setup


Instance 1:
ok 630 should not be in started state
# setup


Instance 2:
ok 630 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.555Z - info: Running on ios test: 172. functions are run from a queue in the right order


Instance 3:
ok 632 should be in started state


Instance 1:
ok 631 should be in started state
# 172. functions are run from a queue in the right order


Instance 3:
# 172. functions are run from a queue in the right order


Instance 2:
ok 631 should be in started state


Instance 2:
# 172. functions are run from a queue in the right order


Instance 3:
ok 633 call order must match


Instance 3:
# teardown


Instance 1:
ok 632 call order must match


Instance 1:
# teardown


Instance 2:
ok 632 call order must match


Instance 2:
# teardown


Instance 3:
ok 634 should not be in started state
# setup


Instance 1:
ok 633 should not be in started state


Instance 1:
# setup


Instance 2:
ok 633 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.581Z - info: Running on ios test: 173. network changes are ignored while stopping


Instance 3:
ok 635 should be in started state
# 173. network changes are ignored while stopping


Instance 1:
ok 634 should be in started state
# 173. network changes are ignored while stopping


Instance 2:
ok 634 should be in started state


Instance 2:
# 173. network changes are ignored while stopping


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 635 should not be called


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 636 should not be called


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 635 should not be called


Instance 2:
# teardown


Instance 1:
ok 636 should not be in started state


Instance 1:
# setup


Instance 3:
ok 637 should not be in started state


Instance 2:
ok 636 should not be in started state


Instance 3:
# setup


Instance 2:
# setup


2016-03-29T08:09:05.601Z - info: Running on ios test: 174. #startListeningForAdvertisements returns error if wifi is off and fires event when on


Instance 1:
ok 637 should be in started state


Instance 3:
ok 638 should be in started state


Instance 1:
# 174. #startListeningForAdvertisements returns error if wifi is off and fires event when on


Instance 3:
# 174. #startListeningForAdvertisements returns error if wifi is off and fires event when on


Instance 2:
ok 637 should be in started state


Instance 2:
# 174. #startListeningForAdvertisements returns error if wifi is off and fires event when on


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 638 wifi should be off
ok 639 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 640 discoveryActive should be true


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 639 wifi should be off
ok 640 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 641 discoveryActive should be true


Instance 1:
# teardown


Instance 3:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 638 wifi should be off


Instance 2:
ok 639 specific error expected


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 640 discoveryActive should be true


Instance 2:
# teardown


Instance 1:
ok 641 should not be in started state
# setup


Instance 3:
ok 642 should not be in started state


Instance 3:
# setup


Instance 2:
ok 641 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.624Z - info: Running on ios test: 175. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on


Instance 3:
ok 643 should be in started state


Instance 1:
ok 642 should be in started state
# 175. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on


Instance 3:
# 175. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on


Instance 2:
ok 642 should be in started state
# 175. #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 643 wifi should be off
ok 644 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 644 wifi should be off
ok 645 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 646 advertisingActive should be true


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 643 wifi should be off
ok 644 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
# teardown


Instance 1:
ok 645 advertisingActive should be true


Instance 1:
# teardown


Instance 2:
ok 645 advertisingActive should be true


Instance 2:
# teardown


Instance 1:
ok 646 should not be in started state


Instance 1:
# setup


Instance 3:
ok 647 should not be in started state


Instance 3:
# setup


Instance 2:
ok 646 should not be in started state


Instance 2:
# setup


2016-03-29T08:09:05.650Z - info: Running on ios test: 176. when wifi is enabled discovery is activated and peers become available


Instance 1:
ok 647 should be in started state


Instance 1:
# 176. when wifi is enabled discovery is activated and peers become available


Instance 2:
ok 647 should be in started state


Instance 2:
# 176. when wifi is enabled discovery is activated and peers become available


Instance 3:
ok 648 should be in started state


Instance 3:
# 176. when wifi is enabled discovery is activated and peers become available


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 648 wifi should be off
ok 649 specific error expected


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 649 wifi should be off
ok 650 specific error expected


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 648 wifi should be off


Instance 2:
ok 649 specific error expected


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 3:
ok 651 peer identifier should match
ok 652 host address should match
ok 653 port should match


Instance 2:
ok 650 peer identifier should match
ok 651 host address should match
ok 652 port should match


Instance 1:
ok 650 peer identifier should match
ok 651 host address should match
ok 652 port should match


Instance 3:
# teardown


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
ok 653 should not be in started state
# setup


Instance 2:
ok 653 should not be in started state
# setup


Instance 3:
ok 654 should not be in started state


Instance 3:
# setup


2016-03-29T08:09:06.178Z - info: Running on ios test: 177. #ThaliPeerPoolDefault - single action


Instance 3:
# 177. #ThaliPeerPoolDefault - single action


Instance 1:
# 177. #ThaliPeerPoolDefault - single action


Instance 2:
# 177. #ThaliPeerPoolDefault - single action


Instance 3:
ok 655 is an agent
ok 656 enqueue is fine
ok 657 Everything should be off the queue
# teardown


Instance 1:
ok 654 is an agent
ok 655 enqueue is fine
ok 656 Everything should be off the queue
# teardown


Instance 2:
ok 654 is an agent
ok 655 enqueue is fine


Instance 2:
ok 656 Everything should be off the queue


Instance 2:
# teardown


Instance 1:
# setup


Instance 2:
# setup


Instance 3:
# setup


2016-03-29T08:09:06.193Z - info: Running on ios test: 178. #ThaliPeerPoolDefault - multiple actions


Instance 1:
# 178. #ThaliPeerPoolDefault - multiple actions


Instance 3:
# 178. #ThaliPeerPoolDefault - multiple actions


Instance 2:
# 178. #ThaliPeerPoolDefault - multiple actions


Instance 3:
ok 658 is an agent
ok 659 first enqueue is fine
ok 660 is an agent
ok 661 second enqueue is fine
ok 662 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 663 Queue is empty
# teardown


Instance 2:
ok 657 is an agent
ok 658 first enqueue is fine
ok 659 is an agent
ok 660 second enqueue is fine
ok 661 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 662 Queue is empty
# teardown


Instance 1:
ok 657 is an agent
ok 658 first enqueue is fine
ok 659 is an agent
ok 660 second enqueue is fine
ok 661 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 662 Queue is empty


Instance 1:
# teardown


2016-03-29T08:09:06.210Z - info: Test run on ios complete


2016-03-29T08:09:06.211Z - info: 

-== UNIT TEST RESULTS ==-


2016-03-29T08:09:06.211Z - info: PLATFORM: ios
2016-03-29T08:09:06.211Z - info: RESULT: FAIL
2016-03-29T08:09:06.211Z - info: 178 of 178 tests completed
2016-03-29T08:09:06.211Z - info: 177/178 passed (1 failures)


2016-03-29T08:09:06.212Z - info: 

--- Failed tests ---


2016-03-29T08:09:06.212Z - warn: 40. peer should be found once after listening and discovery started - fail


2016-03-29T08:09:06.212Z - info: 

-== END ==-


TEST FAILED - SEE ABOVE FOR MORE DETAILS
Instance 3:
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


Instance 2:
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


Instance 1:
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET https://registry.npmjs.org/cordova
npm http 200 https://registry.npmjs.org/cordova
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/minimatch
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
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/defined
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 200 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/raw-body
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
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
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/acorn
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
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http 304 https://registry.npmjs.org/yallist
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http 200 https://registry.npmjs.org/commander
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/supports-color
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http 200 https://registry.npmjs.org/strip-ansi
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/espree
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/requizzle
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/js2xmlparser
npm http 304 https://registry.npmjs.org/espree
npm http 304 https://registry.npmjs.org/catharsis
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/requizzle
npm http 304 https://registry.npmjs.org/wrench
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/tweetnacl
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.3.tgz
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
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
npm http 304 https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
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
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/setimmediate
npm http 304 https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm http 200 https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/minimist
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
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/wrapping-tape
npm http request GET https://registry.npmjs.org/uuid
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.11.1.tgz
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/pouchdb
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/proxyquire
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tmp
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/supertest
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/tape-catch
npm http 304 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/wrapping-tape
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/randomstring
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.11.1.tgz
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/nock
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
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/utils-merge
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
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/multiparty
npm http 200 https://registry.npmjs.org/cookie-parser
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-auth
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/compressible
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 304 https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/meow
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
npm http 304 https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 304 https://registry.npmjs.org/repeating
npm http 304 https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 304 https://registry.npmjs.org/aproba
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/websql
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 200 https://registry.npmjs.org/websql
npm http 304 https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/level-errors
npm http 200 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
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
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/forever-agent
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
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
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
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
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/noop-fn
npm http request GET https://registry.npmjs.org/sqlite3
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/noop-fn
npm http 200 https://registry.npmjs.org/sqlite3
npm http request GET https://registry.npmjs.org/nan
npm http 200 https://registry.npmjs.org/nan
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/xmlhttprequest-cookie
npm http request GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/jshint
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 200 https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/exit
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/shelljs
npm http 200 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 200 https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domutils
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/domelementtype
npm http 304 https://registry.npmjs.org/entities
npm http request GET https://registry.npmjs.org/dom-serializer
npm http 304 https://registry.npmjs.org/dom-serializer
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/extend
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
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/mkdirp
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/propagate
npm http request GET https://registry.npmjs.org/chai
npm http 304 https://registry.npmjs.org/propagate
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/assertion-error
npm http 304 https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 304 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/samsam
npm http request GET https://registry.npmjs.org/lolex
npm http 304 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/util
npm http 304 https://registry.npmjs.org/lolex
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
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/formidable
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/resolve
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/has
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http request GET https://registry.npmjs.org/define-properties
npm http request GET https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http 304 https://registry.npmjs.org/is-callable
npm http request GET https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
npm WARN prefer global jshint@2.9.1 should be installed with -g
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
Release/obj/gen/sqlite-autoconf-3090100/sqlite3.c:9704:26: warning: unused variable 'sqlite3one' [-Wunused-const-variable]
SQLITE_PRIVATE const int sqlite3one = 1;
                         ^
1 warning generated.
In file included from ../src/database.cc:4:
In file included from ../src/database.h:10:
In file included from ../../nan/nan.h:46:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:143:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/database.cc:227:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/database.cc:505:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/database.cc:605:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
5 warnings generated.
In file included from ../src/node_sqlite3.cc:8:
In file included from ../src/database.h:10:
In file included from ../../nan/nan.h:46:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/statement.cc:3:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/statement.cc:118:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/statement.cc:322:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Bind);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:370:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Get);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:438:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Run);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:504:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(All);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:601:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Each);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:724:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Reset);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
8 warnings generated.
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

Error: Command failed: npm http request GET https://registry.npmjs.org/cordova
npm http 200 https://registry.npmjs.org/cordova
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/rimraf
npm http request GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/minimatch
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
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/negotiator
npm http request GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/stack-trace
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/defined
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http 200 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/raw-body
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
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
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/acorn
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
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http request GET https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http 304 https://registry.npmjs.org/yallist
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chalk
npm http fetch GET https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http 200 https://registry.npmjs.org/commander
npm http fetch 200 https://registry.npmjs.org/chalk/-/chalk-1.1.3.tgz
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/supports-color
npm http fetch GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http 200 https://registry.npmjs.org/strip-ansi
npm http fetch 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.1.tgz
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/espree
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/requizzle
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/js2xmlparser
npm http 304 https://registry.npmjs.org/espree
npm http 304 https://registry.npmjs.org/catharsis
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/requizzle
npm http 304 https://registry.npmjs.org/wrench
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/tweetnacl
npm http fetch GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.3.tgz
npm http fetch 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.3.tgz
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
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
npm http 304 https://registry.npmjs.org/adm-zip
npm http 200 https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
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
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/pinkie
npm http request GET https://registry.npmjs.org/hoek
npm http request GET https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/setimmediate
npm http 304 https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 200 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm http 200 https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/minimist
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
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/wrapping-tape
npm http request GET https://registry.npmjs.org/uuid
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/multiplex
npm http fetch GET https://registry.npmjs.org/bn.js/-/bn.js-4.11.1.tgz
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/pouchdb
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/proxyquire
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/tmp
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/supertest
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/tape-catch
npm http 304 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/supertest-as-promised
npm http 200 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/wrapping-tape
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/randomstring
npm http fetch 200 https://registry.npmjs.org/bn.js/-/bn.js-4.11.1.tgz
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/nock
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
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/inherits
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
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/utils-merge
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
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/multiparty
npm http 200 https://registry.npmjs.org/cookie-parser
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 304 https://registry.npmjs.org/pouchdb-auth
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/compressible
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/meow
npm http 304 https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/meow
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
npm http 304 https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/repeating
npm http 304 https://registry.npmjs.org/repeating
npm http 304 https://registry.npmjs.org/get-stdin
npm http request GET https://registry.npmjs.org/is-finite
npm http 304 https://registry.npmjs.org/is-finite
npm http request GET https://registry.npmjs.org/number-is-nan
npm http 304 https://registry.npmjs.org/number-is-nan
npm http request GET https://registry.npmjs.org/aproba
npm http 304 https://registry.npmjs.org/aproba
npm http request GET https://registry.npmjs.org/double-ended-queue
npm http request GET https://registry.npmjs.org/fruitdown
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/websql
npm http request GET https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/js-extend
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 200 https://registry.npmjs.org/websql
npm http 304 https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/end-stream
npm http 304 https://registry.npmjs.org/end-stream
npm http request GET https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/write-stream
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/level-codec
npm http request GET https://registry.npmjs.org/level-errors
npm http request GET https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/prr
npm http request GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/prr
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http 304 https://registry.npmjs.org/level-errors
npm http 200 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
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
npm http request GET https://registry.npmjs.org/aws-sign2
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/forever-agent
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
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
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/generate-object-property
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
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/noop-fn
npm http request GET https://registry.npmjs.org/sqlite3
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/noop-fn
npm http 200 https://registry.npmjs.org/sqlite3
npm http request GET https://registry.npmjs.org/nan
npm http 200 https://registry.npmjs.org/nan
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/xmlhttprequest-cookie
npm http request GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/xmlhttprequest
npm http request GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 304 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/jshint
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http 200 https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/exit
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/shelljs
npm http 200 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 200 https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domutils
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/domelementtype
npm http 304 https://registry.npmjs.org/entities
npm http request GET https://registry.npmjs.org/dom-serializer
npm http 304 https://registry.npmjs.org/dom-serializer
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/couchdb-render
npm http 304 https://registry.npmjs.org/extend
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
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/bindings
npm http request GET https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/mkdirp
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/propagate
npm http request GET https://registry.npmjs.org/chai
npm http 304 https://registry.npmjs.org/propagate
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/assertion-error
npm http 304 https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http 304 https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 304 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/samsam
npm http request GET https://registry.npmjs.org/lolex
npm http 304 https://registry.npmjs.org/formatio
npm http 304 https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/util
npm http 304 https://registry.npmjs.org/lolex
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
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/utf8
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/ultron
npm http request GET https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.3.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/formidable
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/resolve
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/has
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http request GET https://registry.npmjs.org/define-properties
npm http request GET https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http 304 https://registry.npmjs.org/is-callable
npm http request GET https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-symbol
npm http 304 https://registry.npmjs.org/is-date-object
npm http request GET https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/os-tmpdir
npm WARN prefer global jshint@2.9.1 should be installed with -g
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
Release/obj/gen/sqlite-autoconf-3090100/sqlite3.c:9704:26: warning: unused variable 'sqlite3one' [-Wunused-const-variable]
SQLITE_PRIVATE const int sqlite3one = 1;
                         ^
1 warning generated.
In file included from ../src/database.cc:4:
In file included from ../src/database.h:10:
In file included from ../../nan/nan.h:46:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:143:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/database.cc:227:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/database.cc:505:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/database.cc:605:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
5 warnings generated.
In file included from ../src/node_sqlite3.cc:8:
In file included from ../src/database.h:10:
In file included from ../../nan/nan.h:46:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
1 warning generated.
In file included from ../src/statement.cc:3:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/statement.cc:118:9: warning: unused variable 'status' [-Wunused-variable]
    int status = uv_queue_work(uv_default_loop(),
        ^
../src/statement.cc:322:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Bind);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:370:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Get);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:438:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Run);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:504:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(All);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:601:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Each);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
../src/statement.cc:724:5: warning: unused variable 'status' [-Wunused-variable]
    STATEMENT_BEGIN(Reset);
    ^
../src/macros.h:125:9: note: expanded from macro 'STATEMENT_BEGIN'
    int status = uv_queue_work(uv_default_loop(),                              \
        ^
8 warnings generated.
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
