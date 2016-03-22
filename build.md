#### Test (Fail) 63458193 Build Logs


```
Cordova version:
6.0.0
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
│ │ └─┬ lru-cache@4.0.0 
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
│ │ ├─┬ chalk@1.1.1 
│ │ │ ├─┬ ansi-styles@2.2.0 
│ │ │ │ └── color-convert@1.0.0 
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
      └── tweetnacl@0.14.1 

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
│ │ └─┬ lru-cache@4.0.0 
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
│ │ ├─┬ chalk@1.1.1 
│ │ │ ├─┬ ansi-styles@2.2.0 
│ │ │ │ └── color-convert@1.0.0 
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
│ │   └── tweetnacl@0.14.1 
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
├── bn.js@4.11.0 
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
│       │ │ │ ├─┬ ansi-styles@2.2.0 
│       │ │ │ │ └── color-convert@1.0.0 
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
│ ├─┬ chalk@1.1.1 
│ │ ├─┬ ansi-styles@2.2.0 
│ │ │ └── color-convert@1.0.0 
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
│ └─┬ superagent@1.8.2 
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
│ │ │ └─┬ lru-cache@4.0.0
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
│ │ │ ├─┬ chalk@1.1.1 
│ │ │ │ ├─┬ ansi-styles@2.2.0 
│ │ │ │ │ └── color-convert@1.0.0 
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
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
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
DEBUG createNativeListener: listening 49778
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49780
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
DEBUG createNativeListener: listening 49783
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
DEBUG createNativeListener: listening 49787
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
DEBUG createNativeListener: listening 49792
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
DEBUG createNativeListener: listening 49796
ok 14 we should not have gotten an error
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 49800
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
DEBUG createNativeListener: listening 49804
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
DEBUG createNativeListener: listening 49808
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
DEBUG createNativeListener: listening 49860
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
DEBUG createNativeListener: listening 49864
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
DEBUG createNativeListener: listening 49867
# teardown
# setup
# calling createPeerListener after calling stop produces error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49868
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49869
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49871
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= true
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
ok 46 should get error
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
DEBUG createNativeListener: creating native server
ok 47 Can call startUpdateAdvertisingAndListening without error
ok 48 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49873
DEBUG createPeerListener: pleaseConnect= true
WARN createPeerListener: outgoing socket - Error: connect ECONNREFUSED
ok 49 reason should be as expected
ok 50 Expected a reject
{ _state: 'started',
  _nativeServer: 
   { domain: null,
     _events: { connection: [Object], error: [Function], close: [Function] },
     _maxListeners: 10,
     _connections: 0,
     connections: [Getter/Setter],
     _handle: 
      { fd: 12,
        writeQueueSize: 0,
        onconnection: [Function: onconnection],
        owner: [Circular] },
     _usingSlaves: false,
     _slaves: [],
     allowHalfOpen: false,
     closeAll: [Function],
     closeAllPromise: [Function],
     _incoming: [],
     _connectionKey: '4:0.0.0.0:0' },
  _peerServers: {},
  _pendingReverseConnections: {},
  _routerPort: 4242,
  _events: { failedConnection: [Function] } }
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
DEBUG createPeerListener: failed incoming connection because of mux promise failure: undefined
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
DEBUG createNativeListener: creating native server
ok 56 Can call startUpdateAdvertisingAndListening without error
ok 57 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49880
DEBUG createPeerListener: pleaseConnect= true
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
WARN createPeerListener: 
DEBUG createPeerListener: failedConnection
ok 74 failed connection should reject with error
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
DEBUG createNativeListener: creating native server
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49895
DEBUG createPeerListener: pleaseConnect= true
ok 77 Should get spontaneous connection
ok 78 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === true
DEBUG createNativeListener: creating native server
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49898
DEBUG createPeerListener: pleaseConnect= true
WARN createPeerListener: was expecting a forward connection to be made
ok 81 reason should be as expected
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
DEBUG createNativeListener: creating native server
ok 82 Can call startUpdateAdvertisingAndListening without error
ok 83 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49900
DEBUG createPeerListener: pleaseConnect= false
ok 84 peerPort should not be nativePort
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  0
DEBUG createPeerListener: timed out waiting for incoming connection
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  0
DEBUG createPeerListener: no mux found
ok 85 should not get event until connection is made
ok 86 reason should be as expected
DEBUG createPeerListener: failed incoming connection because of mux promise failure: AssertionError: server._mux must exist by now
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
DEBUG createNativeListener: creating native server
ok 87 Can call startUpdateAdvertisingAndListening without error
ok 88 Can call startListeningForAdvertisements without error
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
ok 89 sent and received should be the same
# teardown
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
DEBUG createNativeListener: creating native server
ok 90 Can call startUpdateAdvertisingAndListening without error
ok 91 Can call startListeningForAdvertisements without error
DEBUG createPeerListener: createPeerListener
DEBUG createNativeListener: listening 49907
DEBUG createPeerListener: pleaseConnect= false
DEBUG createPeerListener: first connection
DEBUG createPeerListener: looking up mux for client port:  49910
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createPeerListener: reverse connection
DEBUG createPeerListener: looking up mux for client port:  49910
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: 
ok 92 should get routerPortConnectionFailed
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
ok 93 expect a specific error when the connection is closed
ok 94 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
ok 95 expect a specific error when the connection is closed
ok 96 not possible to connect to the server anymore
# teardown
# setup
# multiplex can send data
ok 97 String should be length:200
# teardown
# setup
# enqueue and run in order
ok 98 firstPromise setTimeout
ok 99 firstPromise result
ok 100 firstPromise testValue
ok 101 secondPromise setTimeout
ok 102 secondPromise result
ok 103 secondPromise testValue
ok 104 thirdPromise in promise
ok 105 thirdPromise result
ok 106 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 107 thirdPromise - first to run
ok 108 thirdPromise - in resolve
ok 109 secondPromise - second to run
ok 110 secondPromise - in catch
ok 111 firstPromise - third to run
ok 112 firstPromise - in then
ok 113 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 114 fourth
ok 115 fourth
ok 116 second
ok 117 secondPromise - in then
ok 118 first
ok 119 firstPromise - in catch
ok 120 third
ok 121 thirdPromise - in then
ok 122 testingPromises
# teardown
# setup
# queues handled independently
ok 123 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 124 sane
# teardown
# setup
# another
ok 125 sane
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 126 specific error should be returned
# teardown
ok 127 error should be null
ok 128 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 129 specific error should be returned
# teardown
ok 130 error should be null
ok 131 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49930
ok 132 error should be null
ok 133 error should be null
ok 134 error should be null
ok 135 error should be null
# teardown
ok 136 error should be null
ok 137 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49932
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 138 error should be null
ok 139 error should be null
ok 140 error should be null
ok 141 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 142 error should be null
ok 143 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49934
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 144 error should be null
ok 145 error should be null
ok 146 error should be null
ok 147 error should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 148 error should be null
ok 149 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49939
ok 150 error should be null
ok 151 error should be null
ok 152 error should be null
ok 153 error should be null
# teardown
ok 154 error should be null
ok 155 error should be null
# setup
# #start should fail if called twice in a row
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49941
ok 156 first call should succeed
ok 157 first call should succeed
ok 158 specific error should be returned
# teardown
ok 159 error should be null
ok 160 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49943
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 161 called only once
ok 162 discovery state matches
ok 163 advertising state matches
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 164 error should be null
ok 165 error should be null
# setup
# does not send duplicate availability changes
ok 166 should be called once
ok 167 should not have been called more than once
# teardown
ok 168 error should be null
ok 169 error should be null
# setup
# can get the network status
ok 170 network status should have certain non-empty properties
# teardown
ok 171 error should be null
ok 172 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
ok 173 host address should match
ok 174 port should match
ok 175 host address should be null
ok 176 port should should be null
# teardown
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 177 error should be null
ok 178 error should be null
# setup
# network changes emitted correctly
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49948
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 179 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 180 wifi is on
# teardown
ok 181 error should be null
ok 182 error should be null
# setup
# network changes not emitted in stopped state
ok 183 event was not emitted
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 184 error should be null
ok 185 error should be null
# setup
# calls correct starts when network changes
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49950
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 186 specific error expected
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 187 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
ok 188 startListeningForAdvertisements should have been called
ok 189 startUpdateAdvertisingAndListening should have been called
# teardown
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 190 error should be null
ok 191 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49955
INFO testUtils: Toggling radios to: false
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 192 host address should be null
ok 193 port number should be null
INFO testUtils: Toggling radios to: true
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 194 error should be null
ok 195 error should be null
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# setup
# Can call start/stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 196 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 197 Can call stopListeningForAdvertisements without error
# teardown
ok 198 Should be able to call stopListeningForAdvertisments in teardown
ok 199 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 200 Can call startListeningForAdvertisements without error
ok 201 Can call startListeningForAdvertisements twice without error
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 202 Should be able to call stopListeningForAdvertisments in teardown
ok 203 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 204 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 205 Can call stopAdvertisingAndListening without error
# teardown
ok 206 Should be able to call stopListeningForAdvertisments in teardown
ok 207 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 208 Can call startUpdateAdvertisingAndListening without error
ok 209 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 210 Should be able to call stopListeningForAdvertisments in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 211 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 212 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 213 specific error should be returned
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# should be able to call #stopListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49961
ok 214 no errors
ok 215 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# should be able to call #startListeningForAdvertisements many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49963
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 216 no errors
ok 217 still no errors
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
DEBUG createNativeListener: listening 49965
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 218 no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 219 still no errors
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
# setup
# should be able to call #stopAdvertisingAndListening many times
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49969
ok 220 no errors
ok 221 still no errors
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# can get the network status before starting
ok 222 network status should have certain non-empty properties
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# error returned with bad router
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 223 specific error expected
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# all services are stopped when we call stop
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49971
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
ok 224 connection to servers manager should succeed after starting
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
ok 225 connection to router server should succeed after starting
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 226 is stopped after calling stop
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
ok 227 connection to servers manager should fail after stopping
ok 228 connection to router server should fail after stopping
# teardown
# setup
# make sure terminateConnection is properly hooked up
ok 229 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# make sure terminateListener is properly hooked up
ok 230 called with right arguments
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# make sure we actually call kill connections properly
ok 231 IMPLEMENT ME!!!!!!
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49979
INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":49978,"error":{}}
ok 232 failure reason is as expected
ok 233 error description is as expected
ok 234 must be stopped
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49981
ok 235 peerIdentifier matches
ok 236 error description matches
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# can do HTTP requests between peers without coordinator
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49983
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 237 found a peer! {"peerIdentifier":"foo","portNumber":49986,"hostAddress":"127.0.0.1"}
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
DEBUG createNativeListener: stream close:
DEBUG createPeerListener: error on incoming stream - Error: Channel destroyed
ok 238 server should return 200
ok 239 response body should match testData
# teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
DEBUG createNativeListener: mux close
# setup
# peer changes handled from a queue
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 49994
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
ok 240 peers were handled in the right order
DEBUG createNativeListener: incoming socket close
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50006
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 241 discovery is active
ok 242 advertising is active
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50008
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: 50008
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 243 right error reason
ok 244 Stop should be fine
ok 245 same port
ok 246 we should be off
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50012
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 247 discoveryActive matches
ok 248 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 249 discoveryActive matches
ok 250 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50014
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 251 discoveryActive matches
ok 252 advertisingActive matches
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 253 discoveryActive matches
ok 254 advertisingActive matches
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50018
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 255 peerIdentifier should be hello
ok 256 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 257 good beacon
ok 258 good preAmble
ok 259 public keys match!
ok 260 must return null after successful call
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 261 Response should be HTTP_BAD_RESPONSE
ok 262 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 263 Response should be NETWORK_PROBLEM
ok 264 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Test timeout locally
ok 265 Should be NETWORK_PROBLEM caused by timeout
ok 266 reject reason should be Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 267 Call start once
ok 268 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 269 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 270 Should be Killed
ok 271 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 272 Should be KILLED
ok 273 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 274 Should be KILLED
ok 275 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 276 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 277 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 278 Should be NETWORK_PROBLEM caused closing server socket
ok 279 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 280 Should be NETWORK_PROBLEM caused closing client socket
ok 281 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 282 publicKeysToNotify cannot be null
ok 283 ecdh for local device cannot be null
ok 284 milliseconds cannot be less than 0
ok 285 milliseconds cannot be 0
ok 286 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 287 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 288 should be equal
ok 289 should be equal
ok 290 (unnamed assert)
ok 291 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 292 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 293 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 294 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 295 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 296 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 297 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 298 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 299 should be equal
ok 300 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 301 should be equal
ok 302 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 303 right number of calls to address book
ok 304 good preAmble
ok 305 good unencryptedKeyId
ok 306 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 307 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 308 secrets match
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 309 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 310 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 311 StartUpdateAdvertisingAndListening should not be called
ok 312 ThaliMobile.StopAdvertisingAndListening should be called once
ok 313 no error
ok 314 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 315 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 316 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 317 no error
ok 318 should be 200
ok 319 should be equal
ok 320 should be equal
ok 321 (unnamed assert)
ok 322 no error
ok 323 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 324 error should be null
ok 325 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 326 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 327 getPeerIdentifier
ok 328 getConnectionType
ok 329 getActionType
ok 330 getActionState
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 331 initial state
ok 332 after start
ok 333 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 334 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 335 clean kill
ok 336 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 337 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 338 getHostAddress works
ok 339 getPortNumber works
ok 340 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 341 Entry counter must be 1
ok 342 Size must be 1
ok 343 Entry counter must be 2
ok 344 Size must be 2
ok 345 Entry2 should not be found
ok 346 Size must be 1
ok 347 Size must be 0
ok 348 entry not found must be thrown
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 349 Size must be100
ok 350 Entries between 20 and MAXSIZE + 20 should exist
ok 351 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 352 Entries between 6 and MAXSIZE + 4 should exist
ok 353 Size should be MAXSIZE
ok 354 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 355 WAITING state entry should not be removed
ok 356 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 357 Size should be MAXSIZE
ok 358 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 359 Kill should be called once
ok 360 Size should be 100
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 361 null arg
ok 362 wrong arg type
ok 363 wrong state
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 364 good enqueue
ok 365 should be equal
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 366 good enqueue
ok 367 2nd good enqueue
ok 368 we are in the pool
ok 369 We are out of the pool
ok 370 Action was killed
ok 371 The original kill was called too
ok 372 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 373 good enqueue
ok 374 first kill
ok 375 second NOOP kill
# teardown
# setup
# compareBufferArrays
ok 376 should throw
ok 377 should throw
ok 378 (unnamed assert)
ok 379 (unnamed assert)
ok 380 (unnamed assert)
ok 381 (unnamed assert)
ok 382 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 383 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 384 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 385 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 386 should be equal
ok 387 should be equal
ok 388 should throw
# teardown
# setup
# Test TransientState
ok 389 should throw
ok 390 should throw
ok 391 should be equal
ok 392 should be equal
ok 393 should be equal
ok 394 should be equal
ok 395 (unnamed assert)
ok 396 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 397 verify failed
ok 398 constructor called once
ok 399 constructor called with right args
ok 400 match start arg
ok 401 start called once
ok 402 stop called once
ok 403 stop after start
# teardown
# setup
# One peer and empty DB
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 404 verify failed
ok 405 constructor called once
ok 406 constructor called with right args
ok 407 match start arg
ok 408 start called once
ok 409 stop called once
ok 410 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 411 verify failed
ok 412 constructor called once
ok 413 constructor called with right args
ok 414 match start arg
ok 415 start called once
ok 416 stop called once
ok 417 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 418 verify failed
ok 419 constructor called once
ok 420 constructor called with right args
ok 421 match start arg
ok 422 start called once
ok 423 stop called once
ok 424 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 425 verify failed
ok 426 constructor called once
ok 427 constructor called with right args
ok 428 match start arg
ok 429 start called once
ok 430 stop called once
ok 431 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 432 verify failed
ok 433 constructor called once
ok 434 constructor called with right args
ok 435 match start arg
ok 436 start called once
ok 437 stop called once
ok 438 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 439 verify failed
ok 440 constructor called once
ok 441 constructor called with right args
ok 442 match start arg
ok 443 start called once
ok 444 stop called once
ok 445 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 446 verify failed
ok 447 constructor called once
ok 448 constructor called with right args
ok 449 last start before stop
ok 450 empty first start
ok 451 full second start
ok 452 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 453 verify failed
ok 454 constructor called once
ok 455 constructor called with right args
ok 456 start before stop
ok 457 We got at least 3 calls to start
ok 458 at least 3
ok 459 default 1
ok 460 1 run
ok 461 default 2
ok 462 2 run
ok 463 default 3
# teardown
# setup
# start and stop and start and stop
ok 464 start out null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 465 back to null
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 466 still null
ok 467 verify failed
ok 468 constructor called once
ok 469 constructor called with right args
ok 470 first start before first stop
ok 471 first stop before second start
ok 472 second start before second stop
# teardown
# setup
# two identical starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 473 verify failed
ok 474 constructor called once
ok 475 constructor called with right args
ok 476 (unnamed assert)
# teardown
# setup
# two different starts in a row
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 477 verify failed
ok 478 constructor called once
ok 479 constructor called with right args
ok 480 (unnamed assert)
ok 481 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 482 verify failed
ok 483 constructor called once
ok 484 constructor called with right args
ok 485 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
ok 486 verify failed
ok 487 constructor called once
ok 488 constructor called with right args
ok 489 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 490 should be equal
ok 491 should be equal
# teardown
# setup
# can create servers manager
ok 492 serversManager must not be null
ok 493 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 494 We need to call start first
# teardown
# setup
# can start/stop servers manager
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50050
ok 495 port must be in range
# teardown
# setup
# starting twice resolves with listening port
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50051
ok 496 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50053
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 497 we should be connected
DEBUG createNativeListener: incoming socket close
ok 498 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50055
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50056
# teardown
# setup
ok 499 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 500 peer identifier should match
ok 501 host address should match
ok 502 port should match
ok 503 host address should be null
ok 504 port should should be null
# teardown
ok 505 should not be in started state
# setup
ok 506 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
ok 507 USN should have changed from the first one
ok 508 when receiving the second byebye, the first USN should be already set
# teardown
ok 509 should not be in started state
# setup
ok 510 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
ok 511 should not have emitted with invalid port
WARN thaliWifiInfrastructure: Received an invalid USN value: 
ok 512 should not have emitted with invalid USN
# teardown
ok 513 should not be in started state
# setup
ok 514 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 515 irrelevant messages should be ignored
ok 516 relevant messages should not be ignored
ok 517 messages from this device should be ignored
# teardown
ok 518 should not be in started state
# setup
ok 519 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 520 specific error should be returned
# teardown
ok 521 should not be in started state
# setup
ok 522 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 523 specific error should be returned
# teardown
ok 524 should not be in started state
# setup
ok 525 should be in started state
# #start should fail if called twice in a row
ok 526 specific error should be received
# teardown
ok 527 should not be in started state
# setup
ok 528 should be in started state
# should not be started after stop is called
ok 529 should not be started
ok 530 should not be listening
ok 531 should not target listening
ok 532 should not be advertising
ok 533 should not target advertising
# teardown
ok 534 should not be in started state
# setup
ok 535 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 536 specific error should be received
# teardown
ok 537 should not be in started state
# setup
ok 538 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
ok 539 specific error expected
# teardown
ok 540 should not be in started state
# setup
ok 541 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
ok 542 server should respond with code 200
# teardown
ok 543 should not be in started state
# setup
ok 544 should be in started state
# #stop can be called multiple times in a row
ok 545 should be in stopped state
ok 546 should still be in stopped state
# teardown
ok 547 should not be in started state
# setup
ok 548 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 549 should be in listening state
ok 550 should still be in listening state
# teardown
ok 551 should not be in started state
# setup
ok 552 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 553 should not be in listening state
ok 554 should still not be in listening state
# teardown
ok 555 should not be in started state
# setup
ok 556 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 557 should not be in advertising state
ok 558 should still not be in advertising state
# teardown
ok 559 should not be in started state
# setup
ok 560 should be in started state
# functions are run from a queue in the right order
ok 561 call order must match
# teardown
ok 562 should not be in started state
# setup
ok 563 should be in started state
# network changes are ignored while stopping
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 564 should not be called
# teardown
ok 565 should not be in started state
# setup
ok 566 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 567 wifi should be off
ok 568 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 569 discoveryActive should be true
# teardown
ok 570 should not be in started state
# setup
ok 571 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 572 wifi should be off
ok 573 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 574 advertisingActive should be true
# teardown
ok 575 should not be in started state
# setup
ok 576 should be in started state
# when wifi is enabled discovery is activated and peers become available
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 577 wifi should be off
ok 578 specific error expected
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 579 peer identifier should match
ok 580 host address should match
ok 581 port should match
# teardown
ok 582 should not be in started state
# setup
# #ThaliPeerPoolDefault - single action
ok 583 is an agent
ok 584 enqueue is fine
ok 585 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 586 is an agent
ok 587 first enqueue is fine
ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 591 Queue is empty
# teardown

1..591
# tests 591
# pass  591

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
Adding Thali Cordova plugin from: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2406bVIqqR7q4wN6/TestApp/thaliDontCheckIn/Thali_CordovaPlugin-npmv2.1.0
Running jx npm install in: /var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2406bVIqqR7q4wN6/TestApp/plugins/org.thaliproject.p2p/scripts
scripts@0.0.1 /private/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2406bVIqqR7q4wN6/TestApp/plugins/org.thaliproject.p2p/scripts
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
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/graceful-fs
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
/var/folders/l4/5qwy3_rs54b7gxzyfpwqt8hc0000gn/T/tmp-2406bVIqqR7q4wN6
ok 14 no error returned when creating a subfolder
# teardown
# setup
# can call hasRequiredHardware
ok 15 resolves with a boolean
# teardown
# setup
# should get right number of setup emits
Required number of ios devices presented (2)
Starting unit test run for platform: ios
Running on ios test: test-1
Required number of android devices presented (2)
Starting unit test run for platform: android
Running on android test: test-1
ok 16 received right amount of setup commands from the server
# teardown
# setup
# should discard surplus devices
Required number of ios devices presented (2)
Starting unit test run for platform: ios
Discarding surplus device: ios device 2
ok 17 should have discarded the extra device
# teardown
StopBroadcasting went ok

1..17
# tests 17
# pass  17

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-coordinated /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runCoordinatedTests.js

2016-03-22T17:32:16.129Z - info: listening on *:3000


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
My device name is: 76ed2afb-90a9-4c6a-bfa8-ba12ac8911f4


Instance 2:
Unit Test app is loaded


Instance 2:
DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
My device name is: 2c49109c-f0c8-4e13-8daf-211c6ecb9f2c


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js


Instance 2:
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
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js


Instance 2:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


Instance 1:
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testthaliPeerPoolDefault.js


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


2016-03-22T17:32:17.333Z - debug: Device presented: 76ed2afb-90a9-4c6a-bfa8-ba12ac8911f4 (ios) unittest socket:0


2016-03-22T17:32:17.340Z - debug: Device presented: 2c49109c-f0c8-4e13-8daf-211c6ecb9f2c (ios) unittest socket:1


2016-03-22T17:32:17.340Z - info: Required number of ios devices presented (2)


2016-03-22T17:32:17.341Z - info: Starting unit test run for platform: ios


Instance 2:
TAP version 13


Instance 2:
# setup


Instance 2:
# 1. calling createNativeListener directly rejects


Instance 1:
TAP version 13


2016-03-22T17:32:17.408Z - info: Running on ios test: 1. calling createNativeListener directly rejects


Instance 1:
# setup


Instance 1:
# 1. calling createNativeListener directly rejects


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50094


Instance 1:
DEBUG createNativeListener: listening 50095


Instance 1:
ok 1 Should throw
# setup


Instance 2:
ok 1 Should throw


Instance 2:
# setup


Instance 1:
# 2. emits incomingConnectionState


Instance 2:
# 2. emits incomingConnectionState


2016-03-22T17:32:17.435Z - info: Running on ios test: 2. emits incomingConnectionState


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50099


Instance 2:
DEBUG createNativeListener: listening 50098


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
ok 2 initial connection state should be CONNECTED


Instance 1:
ok 2 initial connection state should be CONNECTED


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
ok 3 final connection state should be DISCONNECTED


Instance 1:
# setup


Instance 2:
ok 3 final connection state should be DISCONNECTED


Instance 2:
# setup


Instance 1:
# 3. emits routerPortConnectionFailed


Instance 2:
# 3. emits routerPortConnectionFailed


2016-03-22T17:32:17.464Z - info: Running on ios test: 3. emits routerPortConnectionFailed


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50104


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: listening 50106


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: 


Instance 1:
ok 4 tried to connect to right port
ok 5 failed due to refused connection


Instance 1:
ok 6 routerPortConnectionFailed is emitted


Instance 1:
# setup


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: 


Instance 2:
ok 4 tried to connect to right port


Instance 2:
ok 5 failed due to refused connection


Instance 2:
ok 6 routerPortConnectionFailed is emitted


Instance 2:
# setup


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
# 4. native server connections all up


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
# 4. native server connections all up


Instance 2:
DEBUG createNativeListener: incoming socket close


2016-03-22T17:32:17.497Z - info: Running on ios test: 4. native server connections all up


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50112


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50113


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 1:
DEBUG createNativeListener: creating incoming mux


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
ok 7 Send/recvd #1 should be equal length


Instance 1:
ok 7 Send/recvd #1 should be equal length


Instance 1:
ok 8 Send/recvd #1 should be same


Instance 2:
ok 8 Send/recvd #1 should be same


Instance 1:
ok 9 Send/recvd #2 should be equal length


Instance 1:
ok 10 Send/recvd #2 should be same


Instance 2:
ok 9 Send/recvd #2 should be equal length


Instance 1:
ok 11 Should be exactly 2 client sockets


Instance 2:
ok 10 Send/recvd #2 should be same


Instance 2:
ok 11 Should be exactly 2 client sockets


Instance 1:
# setup


Instance 2:
# setup


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
# 5. native server - closing incoming stream cleans outgoing socket


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
# 5. native server - closing incoming stream cleans outgoing socket


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


2016-03-22T17:32:17.535Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50122


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: listening 50123


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
# setup


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
ok 12 socket shouldn't close until after stream


Instance 1:
ok 13 incoming remains open


Instance 1:
# setup


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
# 6. native server - closing incoming connection cleans outgoing socket
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
# 6. native server - closing incoming connection cleans outgoing socket


Instance 1:
DEBUG createNativeListener: incoming socket close


2016-03-22T17:32:17.562Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50130


Instance 1:
DEBUG createNativeListener: listening 50131


Instance 2:
ok 14 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
ok 14 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up


Instance 2:
# setup


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
ok 15 socket shouldn't close until after incoming


Instance 1:
ok 16 incoming is cleaned up


Instance 1:
# setup


Instance 2:
# 7. native server - closing outgoing socket cleans associated mux stream


Instance 1:
# 7. native server - closing outgoing socket cleans associated mux stream


2016-03-22T17:32:17.585Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50139


Instance 2:
DEBUG createNativeListener: listening 50138


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 2:
ok 17 stream was closed


Instance 2:
ok 18 incoming should survive


Instance 2:
ok 19 mux should have no streams


Instance 2:
# setup


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
ok 17 stream was closed


Instance 1:
ok 18 incoming should survive


Instance 1:
ok 19 mux should have no streams


Instance 1:
# setup


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
# 8. native server - closing the whole server cleans everything up


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
# 8. native server - closing the whole server cleans everything up


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


2016-03-22T17:32:17.618Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50146


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
ok 20 we should not have gotten an error
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: listening 50148


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux


Instance 2:
ok 21 Buffers are identical


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new mux


Instance 2:
# setup


Instance 1:
ok 20 we should not have gotten an error


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 21 Buffers are identical


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
ok 22 native server is nulled out


Instance 1:
ok 23 native server should be closed


Instance 1:
ok 24 incoming has been removed


Instance 1:
ok 25 Incoming should be done


Instance 1:
ok 26 The mux object should be closed
ok 27 The mux stream should be closed


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
# setup


Instance 2:
# 9. native server - we can get a ton of connections and data through and still clean up the server completely


Instance 1:
# 9. native server - we can get a ton of connections and data through and still clean up the server completely


2016-03-22T17:32:17.645Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50154


Instance 1:
DEBUG createNativeListener: listening 50155


Instance 2:
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


Instance 1:
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


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
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


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


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


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


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


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
ok 28 native server is nulled out


Instance 2:
ok 29 native server should be closed


Instance 2:
ok 30 incoming has been removed


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
DEBUG createNativeListener: incoming socket close


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


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 2:
# setup


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 1:
ok 28 native server is nulled out


Instance 1:
ok 29 native server should be closed


Instance 1:
ok 30 incoming has been removed


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close


Instance 1:
# setup


Instance 1:
# 10. native server - simulate mux failure, make sure everything is cleaned up


Instance 2:
# 10. native server - simulate mux failure, make sure everything is cleaned up


2016-03-22T17:32:17.809Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50258


Instance 1:
ok 31 we should not have gotten an error


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


Instance 1:
ok 32 Buffers are identical


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: incoming socket close


Instance 1:
ok 33 server should be fine


Instance 1:
ok 34 server should be open
ok 35 incoming has been removed


Instance 2:
DEBUG createNativeListener: listening 50261


Instance 1:
ok 36 The mux object should be closed


Instance 1:
ok 37 The mux stream should be closed


Instance 2:
DEBUG createNativeListener: new incoming socket


Instance 2:
DEBUG createNativeListener: creating incoming mux


Instance 2:
DEBUG createNativeListener: new mux


Instance 1:
# setup


Instance 2:
ok 31 we should not have gotten an error
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket


Instance 2:
ok 32 Buffers are identical


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 33 server should be fine


Instance 2:
ok 34 server should be open


Instance 2:
ok 35 incoming has been removed


Instance 2:
ok 36 The mux object should be closed


Instance 2:
ok 37 The mux stream should be closed


Instance 2:
# setup


Instance 2:
# 11. native server - timing out the incoming connection cleans everything up


Instance 1:
# 11. native server - timing out the incoming connection cleans everything up


2016-03-22T17:32:17.838Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50266


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50268


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


Instance 2:
DEBUG createNativeListener: new mux


Instance 2:
ok 38 we should not have gotten an error


Instance 2:
DEBUG createNativeListener: new stream: 


Instance 2:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 38 we should not have gotten an error


Instance 2:
ok 39 Buffers are identical


Instance 1:
DEBUG createNativeListener: new stream: 


Instance 1:
DEBUG createNativeListener: new outgoing socket


Instance 1:
ok 39 Buffers are identical


Instance 2:
DEBUG createNativeListener: incoming socket timeout


Instance 2:
DEBUG createNativeListener: stream close:


Instance 2:
DEBUG createNativeListener: mux close


Instance 1:
DEBUG createNativeListener: incoming socket timeout


Instance 2:
DEBUG createNativeListener: incoming socket close


Instance 2:
ok 40 server should be fine


Instance 2:
ok 41 server should be open


Instance 2:
ok 42 incoming has been removed


Instance 2:
ok 43 The mux object should be closed


Instance 2:
ok 44 The mux stream should be closed


Instance 2:
# setup


Instance 1:
DEBUG createNativeListener: stream close:


Instance 1:
DEBUG createNativeListener: mux close


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


Instance 1:
# setup


Instance 2:
# 12. closeAll can close even when connections open


Instance 1:
# 12. closeAll can close even when connections open


2016-03-22T17:32:17.872Z - info: Running on ios test: 12. closeAll can close even when connections open


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
ok 45 not possible to connect to the server anymore


Instance 2:
# setup


Instance 1:
ok 45 not possible to connect to the server anymore


Instance 1:
# setup


Instance 2:
# 13. closeAll with promise


Instance 1:
# 13. closeAll with promise


2016-03-22T17:32:17.889Z - info: Running on ios test: 13. closeAll with promise


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
ok 46 not possible to connect to the server anymore


Instance 2:
# setup


Instance 1:
ok 46 not possible to connect to the server anymore


Instance 1:
# setup


Instance 2:
# 14. multiplex can send data


Instance 1:
# 14. multiplex can send data


2016-03-22T17:32:17.909Z - info: Running on ios test: 14. multiplex can send data


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
ok 47 String should be length:200


Instance 1:
# setup


Instance 2:
ok 47 String should be length:200


Instance 2:
# setup


Instance 1:
# 15. enqueue and run in order


Instance 2:
# 15. enqueue and run in order


2016-03-22T17:32:17.924Z - info: Running on ios test: 15. enqueue and run in order


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue


Instance 1:
ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue


Instance 1:
ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue


Instance 2:
ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue


Instance 2:
# setup


Instance 1:
# setup


Instance 2:
# 16. enqueueAtTop and run backwards


Instance 1:
# 16. enqueueAtTop and run backwards


2016-03-22T17:32:18.171Z - info: Running on ios test: 16. enqueueAtTop and run backwards


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
ok 57 thirdPromise - first to run


Instance 2:
ok 58 thirdPromise - in resolve


Instance 2:
ok 59 secondPromise - second to run


Instance 2:
ok 60 secondPromise - in catch


Instance 2:
ok 61 firstPromise - third to run


Instance 2:
ok 62 firstPromise - in then


Instance 2:
ok 63 testing promises


Instance 2:
# setup


Instance 1:
ok 57 thirdPromise - first to run


Instance 1:
ok 58 thirdPromise - in resolve


Instance 1:
ok 59 secondPromise - second to run


Instance 1:
ok 60 secondPromise - in catch


Instance 1:
ok 61 firstPromise - third to run


Instance 1:
ok 62 firstPromise - in then


Instance 1:
ok 63 testing promises


Instance 1:
# setup


Instance 2:
# 17. mix enqueue and enqueueAtTop


Instance 1:
# 17. mix enqueue and enqueueAtTop


2016-03-22T17:32:18.193Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
ok 64 fourth


Instance 2:
ok 65 fourth


Instance 2:
ok 66 second


Instance 2:
ok 67 secondPromise - in then


Instance 1:
ok 64 fourth


Instance 1:
ok 65 fourth


Instance 1:
ok 66 second


Instance 1:
ok 67 secondPromise - in then


Instance 2:
ok 68 first


Instance 2:
ok 69 firstPromise - in catch


Instance 1:
ok 68 first


Instance 2:
ok 70 third


Instance 2:
ok 71 thirdPromise - in then
ok 72 testingPromises


Instance 1:
ok 69 firstPromise - in catch
ok 70 third


Instance 2:
# setup


Instance 1:
ok 71 thirdPromise - in then


Instance 1:
ok 72 testingPromises


Instance 1:
# setup


Instance 1:
# 18. queues handled independently


Instance 2:
# 18. queues handled independently


2016-03-22T17:32:18.322Z - info: Running on ios test: 18. queues handled independently


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
ok 73 all short operations completed before the long resolves


Instance 2:
ok 73 all short operations completed before the long resolves


Instance 2:
# setup


Instance 1:
# setup


Instance 1:
# 19. basic


Instance 2:
# 19. basic


2016-03-22T17:32:18.391Z - info: Running on ios test: 19. basic


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
ok 74 sane


Instance 1:
# setup


Instance 2:
ok 74 sane


Instance 2:
# setup


Instance 2:
# 20. another


Instance 1:
# 20. another


2016-03-22T17:32:18.407Z - info: Running on ios test: 20. another


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
ok 75 sane


Instance 1:
ok 75 sane


Instance 2:
# setup


Instance 1:
# setup


Instance 2:
# 21. #startListeningForAdvertisements should fail if start not called


Instance 1:
# 21. #startListeningForAdvertisements should fail if start not called


2016-03-22T17:32:18.423Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
ok 76 specific error should be returned


Instance 2:
ok 76 specific error should be returned


Instance 2:
# setup


Instance 1:
# setup


Instance 1:
ok 77 error should be null


Instance 2:
ok 77 error should be null
ok 78 error should be null
# 22. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
ok 78 error should be null
# 22. #startUpdateAdvertisingAndListening should fail if start not called


2016-03-22T17:32:18.437Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
ok 79 specific error should be returned


Instance 1:
ok 79 specific error should be returned


Instance 2:
# setup


Instance 1:
# setup


Instance 2:
ok 80 error should be null


Instance 2:
ok 81 error should be null


Instance 2:
# 23. should be able to call #stopListeningForAdvertisements many times


Instance 1:
ok 80 error should be null


Instance 1:
ok 81 error should be null


Instance 1:
# 23. should be able to call #stopListeningForAdvertisements many times


2016-03-22T17:32:18.457Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50290


Instance 1:
DEBUG createNativeListener: listening 50291


Instance 2:
ok 82 error should be null


Instance 2:
ok 83 error should be null


Instance 2:
ok 84 error should be null


Instance 2:
ok 85 error should be null


Instance 2:
# setup


Instance 1:
ok 82 error should be null


Instance 1:
ok 83 error should be null


Instance 1:
ok 84 error should be null


Instance 1:
ok 85 error should be null
# setup


Instance 2:
ok 86 error should be null


Instance 2:
ok 87 error should be null


Instance 2:
# 24. should be able to call #startListeningForAdvertisements many times


Instance 1:
ok 86 error should be null


Instance 1:
ok 87 error should be null


Instance 1:
# 24. should be able to call #startListeningForAdvertisements many times


2016-03-22T17:32:18.483Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50294
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 88 error should be null
ok 89 error should be null
ok 90 error should be null
ok 91 error should be null
# setup


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50295
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 88 error should be null
ok 89 error should be null
ok 90 error should be null
ok 91 error should be null
# setup


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 92 error should be null
ok 93 error should be null
# 25. should be able to call #startUpdateAdvertisingAndListening many times


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 92 error should be null
ok 93 error should be null
# 25. should be able to call #startUpdateAdvertisingAndListening many times


2016-03-22T17:32:18.500Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50298
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 94 error should be null
ok 95 error should be null


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50299
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 94 error should be null
ok 95 error should be null


Instance 2:
ok 96 error should be null
ok 97 error should be null


Instance 1:
ok 96 error should be null
ok 97 error should be null


Instance 2:
# setup


Instance 1:
# setup


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 98 error should be null


Instance 2:
ok 99 error should be null


Instance 2:
# 26. should be able to call #stopAdvertisingAndListening many times


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 98 error should be null


Instance 1:
ok 99 error should be null


Instance 1:
# 26. should be able to call #stopAdvertisingAndListening many times


2016-03-22T17:32:18.526Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50307


Instance 2:
ok 100 error should be null


Instance 2:
ok 101 error should be null


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
ok 102 error should be null
ok 103 error should be null
# setup


Instance 1:
DEBUG createNativeListener: listening 50309


Instance 1:
ok 100 error should be null
ok 101 error should be null


Instance 1:
ok 102 error should be null


Instance 1:
ok 103 error should be null


Instance 1:
# setup


Instance 2:
ok 104 error should be null


Instance 1:
ok 104 error should be null


Instance 2:
ok 105 error should be null
# 27. #start should fail if called twice in a row


Instance 1:
ok 105 error should be null


Instance 1:
# 27. #start should fail if called twice in a row


2016-03-22T17:32:18.546Z - info: Running on ios test: 27. #start should fail if called twice in a row


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50312
ok 106 first call should succeed
ok 107 first call should succeed
ok 108 specific error should be returned
# setup


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50313
ok 106 first call should succeed
ok 107 first call should succeed
ok 108 specific error should be returned
# setup


Instance 1:
ok 109 error should be null
ok 110 error should be null
# 28. does not emit duplicate discoveryAdvertisingStateUpdate


Instance 2:
ok 109 error should be null
ok 110 error should be null
# 28. does not emit duplicate discoveryAdvertisingStateUpdate


2016-03-22T17:32:18.562Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50316
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 111 called only once
ok 112 discovery state matches
ok 113 advertising state matches
# setup


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50317
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 111 called only once
ok 112 discovery state matches
ok 113 advertising state matches


Instance 1:
# setup


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 114 error should be null
ok 115 error should be null


Instance 2:
# 29. does not send duplicate availability changes


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 114 error should be null


Instance 1:
ok 115 error should be null


Instance 1:
# 29. does not send duplicate availability changes


2016-03-22T17:32:18.593Z - info: Running on ios test: 29. does not send duplicate availability changes


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
ok 116 should be called once
ok 117 should not have been called more than once
# setup


Instance 2:
ok 116 should be called once
ok 117 should not have been called more than once
# setup


Instance 2:
ok 118 error should be null
ok 119 error should be null
# 30. can get the network status


Instance 1:
ok 118 error should be null
ok 119 error should be null
# 30. can get the network status


2016-03-22T17:32:18.607Z - info: Running on ios test: 30. can get the network status


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
ok 120 network status should have certain non-empty properties
# setup


Instance 2:
ok 120 network status should have certain non-empty properties
# setup


Instance 1:
ok 121 error should be null
ok 122 error should be null
# 31. wifi peer is marked unavailable if announcements stop


Instance 2:
ok 121 error should be null
ok 122 error should be null
# 31. wifi peer is marked unavailable if announcements stop


2016-03-22T17:32:18.620Z - info: Running on ios test: 31. wifi peer is marked unavailable if announcements stop


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
ok 123 host address should match
ok 124 port should match


Instance 2:
ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined


Instance 2:
ok 123 host address should match


Instance 2:
ok 124 port should match


Instance 1:
ok 125 host address should be null
ok 126 port should should be null


Instance 2:
ok 125 host address should be null
ok 126 port should should be null


Instance 2:
# setup


Instance 1:
# setup


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 127 error should be null
ok 128 error should be null
# 32. network changes emitted correctly


Instance 2:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 127 error should be null
ok 128 error should be null
# 32. network changes emitted correctly


2016-03-22T17:32:19.651Z - info: Running on ios test: 32. network changes emitted correctly


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50327
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 129 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 130 wifi is on


Instance 2:
DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 50328
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 129 wifi is off
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 130 wifi is on
# setup


Instance 1:
# setup


Instance 1:
ok 131 error should be null
ok 132 error should be null
# 33. network changes not emitted in stopped state


Instance 2:
ok 131 error should be null


Instance 2:
ok 132 error should be null


Instance 2:
# 33. network changes not emitted in stopped state


2016-03-22T17:32:19.669Z - info: Running on ios test: 33. network changes not emitted in stopped state


Instance 2:
# teardown


Instance 1:
# teardown


Instance 2:
ok 133 event was not emitted


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
ok 133 event was not emitted


Instance 2:
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
# setup


Instance 1:
ok 134 error should be null


Instance 1:
ok 135 error should be null


Instance 2:
ok 134 error should be null


Instance 2:
ok 135 error should be null


Instance 2:
# 34. calls correct starts when network changes


Instance 1:
# 34. calls correct starts when network changes


2016-03-22T17:32:19.687Z - info: Running on ios test: 34. calls correct starts when network changes


Instance 2:
# teardown


Instance 1:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50331


Instance 1:
DEBUG createNativeListener: listening 50332


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 2:
ok 136 specific error expected


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
ok 136 specific error expected


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
ok 137 specific error expected


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 137 specific error expected


Instance 2:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 138 startListeningForAdvertisements should have been called


Instance 2:
ok 139 startUpdateAdvertisingAndListening should have been called


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
# setup


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}


Instance 1:
DEBUG createPeerListener: createPeerListener


Instance 1:
DEBUG createPeerListener: pleaseConnect= false


Instance 1:
ok 138 startListeningForAdvertisements should have been called


Instance 1:
ok 139 startUpdateAdvertisingAndListening should have been called


Instance 1:
# setup


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


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


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 2:
ok 140 error should be null


Instance 2:
ok 141 error should be null


Instance 2:
# 35. when network connection is lost a peer should be marked unavailable


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 1:
ok 140 error should be null


Instance 1:
ok 141 error should be null


Instance 1:
# 35. when network connection is lost a peer should be marked unavailable


2016-03-22T17:32:19.732Z - info: Running on ios test: 35. when network connection is lost a peer should be marked unavailable


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50346


Instance 1:
DEBUG createNativeListener: listening 50345


Instance 2:
INFO testUtils: Toggling radios to: false


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
INFO testUtils: Toggling radios to: false


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 142 host address should be null


Instance 2:
ok 143 port number should be null


Instance 2:
INFO testUtils: Toggling radios to: true


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
ok 142 host address should be null


Instance 2:
# setup


Instance 1:
ok 143 port number should be null


Instance 1:
INFO testUtils: Toggling radios to: true


Instance 2:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


Instance 2:
ok 144 error should be null


Instance 2:
ok 145 error should be null


Instance 2:
# 36. a peer should be found after #startListeningForAdvertisements is called


Instance 1:
ok 144 error should be null


Instance 1:
ok 145 error should be null


Instance 1:
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}


2016-03-22T17:32:19.757Z - info: Running on ios test: 36. a peer should be found after #startListeningForAdvertisements is called


Instance 1:
# 36. a peer should be found after #startListeningForAdvertisements is called


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
DEBUG createNativeListener: creating native server


Instance 2:
DEBUG createNativeListener: listening 50349


Instance 2:
ok 146 error should be null


Instance 2:
ok 147 error should be null


Instance 1:
DEBUG createNativeListener: creating native server


Instance 1:
DEBUG createNativeListener: listening 50350


Instance 1:
ok 146 error should be null


Instance 1:
ok 147 error should be null


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 148 error should be null


Instance 2:
ok 149 error should be null


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 2:
ok 150 error should be null


Instance 2:
ok 151 error should be null


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 1:
ok 148 error should be null


Instance 1:
ok 149 error should be null


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}


Instance 1:
ok 150 error should be null


Instance 1:
ok 151 error should be null


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 2:
DEBUG createPeerListener: pleaseConnect= false


Instance 2:
ok 152 peer should have a non-empty identifier


Instance 2:
ok 153 peer should have a non-empty host address


Instance 2:
ok 154 peer should have suggested timeout


Instance 2:
ok 155 peer should have port number


Instance 2:
ok 156 peer should have a connection type


Instance 2:
ok 157 connection type should match one of the pre-defined types


Instance 2:
# setup


Instance 1:
DEBUG createPeerListener: createPeerListener
DEBUG createPeerListener: pleaseConnect= false
ok 152 peer should have a non-empty identifier
ok 153 peer should have a non-empty host address
ok 154 peer should have suggested timeout


Instance 2:
DEBUG createPeerListener: createPeerListener


Instance 1:
ok 155 peer should have port number
ok 156 peer should have a connection type


Instance 1:
ok 157 connection type should match one of the pre-defined types


Instance 1:
# setup


Instance 1:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 158 error should be null
ok 159 error should be null
# 37. Can call start/stopListeningForAdvertisements


Instance 2:
INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 158 error should be null
ok 159 error should be null


Instance 2:
# 37. Can call start/stopListeningForAdvertisements


2016-03-22T17:32:20.293Z - info: Running on ios test: 37. Can call start/stopListeningForAdvertisements


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 160 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 161 Can call stopListeningForAdvertisements without error
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 160 Can call startListeningForAdvertisements without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 161 Can call stopListeningForAdvertisements without error
# setup


Instance 2:
ok 162 Should be able to call stopListeningForAdvertisments in teardown
ok 163 Should be able to call stopAdvertisingAndListening in teardown
# 38. Calling startListeningForAdvertisements twice is NOT an error


Instance 1:
ok 162 Should be able to call stopListeningForAdvertisments in teardown
ok 163 Should be able to call stopAdvertisingAndListening in teardown
# 38. Calling startListeningForAdvertisements twice is NOT an error


2016-03-22T17:32:20.306Z - info: Running on ios test: 38. Calling startListeningForAdvertisements twice is NOT an error


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 164 Can call startListeningForAdvertisements without error
ok 165 Can call startListeningForAdvertisements twice without error
# setup


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
ok 164 Can call startListeningForAdvertisements without error
ok 165 Can call startListeningForAdvertisements twice without error
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 166 Should be able to call stopListeningForAdvertisments in teardown
ok 167 Should be able to call stopAdvertisingAndListening in teardown
# 39. Can call start/stopUpdateAdvertisingAndListening


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 166 Should be able to call stopListeningForAdvertisments in teardown
ok 167 Should be able to call stopAdvertisingAndListening in teardown
# 39. Can call start/stopUpdateAdvertisingAndListening


2016-03-22T17:32:20.321Z - info: Running on ios test: 39. Can call start/stopUpdateAdvertisingAndListening


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 168 Can call startUpdateAdvertisingAndListening without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 168 Can call startUpdateAdvertisingAndListening without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 169 Can call stopAdvertisingAndListening without error


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 169 Can call stopAdvertisingAndListening without error
# setup


Instance 1:
# setup


Instance 1:
ok 170 Should be able to call stopListeningForAdvertisments in teardown
ok 171 Should be able to call stopAdvertisingAndListening in teardown
# 40. Calling startUpdateAdvertisingAndListening twice is NOT an error


Instance 2:
ok 170 Should be able to call stopListeningForAdvertisments in teardown
ok 171 Should be able to call stopAdvertisingAndListening in teardown
# 40. Calling startUpdateAdvertisingAndListening twice is NOT an error


2016-03-22T17:32:20.336Z - info: Running on ios test: 40. Calling startUpdateAdvertisingAndListening twice is NOT an error


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 172 Can call startUpdateAdvertisingAndListening without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 172 Can call startUpdateAdvertisingAndListening without error


Instance 2:
ok 173 Can call startUpdateAdvertisingAndListening twice without error


Instance 2:
# setup


Instance 1:
ok 173 Can call startUpdateAdvertisingAndListening twice without error
# setup


Instance 1:
ok 174 Should be able to call stopListeningForAdvertisments in teardown


Instance 2:
ok 174 Should be able to call stopListeningForAdvertisments in teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 175 Should be able to call stopAdvertisingAndListening in teardown
# 41. peerAvailabilityChange is called


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}


Instance 2:
ok 175 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
# 41. peerAvailabilityChange is called


2016-03-22T17:32:20.352Z - info: Running on ios test: 41. peerAvailabilityChange is called


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 176 Can call startUpdateAdvertisingAndListeningwithout error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 177 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 176 Can call startUpdateAdvertisingAndListeningwithout error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 177 Can call startListeningForAdvertisements without error
ok 178 peers must be an array
ok 179 peers must not be zero-length
ok 180 peer must have peerIdentifier
ok 181 peerIdentifier must be a string
ok 182 peer must have peerAvailable
ok 183 peer must have pleaseConnect


Instance 2:
ok 178 peers must be an array
ok 179 peers must not be zero-length
ok 180 peer must have peerIdentifier
ok 181 peerIdentifier must be a string
ok 182 peer must have peerAvailable
ok 183 peer must have pleaseConnect
# setup


Instance 1:
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 184 Should be able to call stopListeningForAdvertisments in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 185 Should be able to call stopAdvertisingAndListening in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 184 Should be able to call stopListeningForAdvertisments in teardown
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 185 Should be able to call stopAdvertisingAndListening in teardown
# 42. Can connect to a remote peer


2016-03-22T17:32:20.371Z - info: Running on ios test: 42. Can connect to a remote peer


Instance 1:
# 42. Can connect to a remote peer


Instance 1:
# teardown


Instance 2:
# teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 186 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 187 Can call startListeningForAdvertisements without error


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 186 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 187 Can call startListeningForAdvertisements without error


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:8833ba63-aa42-4d54-8b94-c54fdab765f7","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:b64c7fce-0294-4b2d-b666-68f2973c40ff","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 1:
INFO testThaliMobileNative: 
ok 188 Must have listeningPort
ok 189 listeningPort must be a number
ok 190 Connection must have clientPort
ok 191 clientPort must be a number
ok 192 Connection must have serverPort
ok 193 serverPort must be a number
ok 194 forward connection must have clientPort == 0
ok 195 forward connection must have serverPort == 0
# setup


Instance 2:
INFO testThaliMobileNative: 
ok 188 Must have listeningPort
ok 189 listeningPort must be a number
ok 190 Connection must have clientPort
ok 191 clientPort must be a number
ok 192 Connection must have serverPort
ok 193 serverPort must be a number
ok 194 forward connection must have clientPort == 0
ok 195 forward connection must have serverPort == 0
# setup


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 196 Should be able to call stopListeningForAdvertisments in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}


Instance 2:
ok 196 Should be able to call stopListeningForAdvertisments in teardown


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 197 Should be able to call stopAdvertisingAndListening in teardown
# 43. Can shift large amounts of data


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
ok 197 Should be able to call stopAdvertisingAndListening in teardown


Instance 1:
# 43. Can shift large amounts of data


2016-03-22T17:32:20.498Z - info: Running on ios test: 43. Can shift large amounts of data


Instance 1:
# teardown


Instance 2:
# teardown


Instance 1:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 198 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 199 Can call startListeningForAdvertisements without error


Instance 2:
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
ok 198 Can call startUpdateAdvertisingAndListening without error
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
ok 199 Can call startListeningForAdvertisements without error
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 1:
DEBUG wifiBasedNativeMock: proxy socket connected


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 2:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:bfe83d83-5cd2-4932-916e-69b67cff5cd5","peerAvailable":true,"pleaseConnect":false}]


Instance 1:
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"urn:uuid:a9b2b617-f99b-4bb2-bd14-4e3780919fa3","peerAvailable":true,"pleaseConnect":false}]



npm http request GET https://registry.npmjs.org/cordova
npm http 200 https://registry.npmjs.org/cordova
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
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
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 200 https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/javascript-state-machine
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/iconv-lite
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
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
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
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
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
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
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
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/color-convert
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
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
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/espree
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/catharsis
npm http 304 https://registry.npmjs.org/requizzle
npm http 304 https://registry.npmjs.org/espree
npm http 304 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/wrench
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/jxc
npm http 304 https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inflight
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
npm http request GET https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/adm-zip
npm http 304 https://registry.npmjs.org/progress
npm http 304 https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
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
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
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
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http 304 https://registry.npmjs.org/yallist
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
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/color-convert
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
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
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/match-stream
npm http request GET https://registry.npmjs.org/setimmediate
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 304 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm http 200 https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/uuid
npm http request GET https://registry.npmjs.org/wrapping-tape
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/proxyquire
npm http 304 https://registry.npmjs.org/sinon
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/supertest
npm http 304 https://registry.npmjs.org/supertest-as-promised
npm http 304 https://registry.npmjs.org/tmp
npm http 304 https://registry.npmjs.org/tape-catch
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/pouchdb
npm http 200 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/wrapping-tape
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
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
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
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/path-to-regexp
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/cookie-parser
npm http 304 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.0.1.tgz
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.0.1.tgz
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/compressible
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/stream-counter
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
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
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/meow
npm http request GET https://registry.npmjs.org/concat-stream
npm http 304 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/camelcase-keys
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/get-stdin
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
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/websql
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/websql
npm http 304 https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/abstract-leveldown
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
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-codec
npm http 200 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/level-errors
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 304 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http request GET https://registry.npmjs.org/has-localstorage
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
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
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/lru-cache
npm http fetch GET https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.1.tgz
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/color-convert
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
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/noop-fn
npm http request GET https://registry.npmjs.org/sqlite3
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/sqlite3
npm http fetch GET https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.2.tgz
npm http 304 https://registry.npmjs.org/noop-fn
npm http fetch 200 https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.2.tgz
npm http request GET https://registry.npmjs.org/nan
npm http 304 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-2.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-2.2.0.tgz
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
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/htmlparser2
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/exit
npm http 304 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/lodash
npm http 200 https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/sigmund
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domelementtype
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domutils
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
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/propagate
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 304 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/assertion-error
npm http 304 https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http 304 https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 304 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/util
npm http 304 https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/lolex
npm http 304 https://registry.npmjs.org/formatio
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
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.2.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/formidable
npm http 304 https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/has
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http request GET https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http 304 https://registry.npmjs.org/is-regex
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

```

Error: Command failed: npm http request GET https://registry.npmjs.org/cordova
npm http 200 https://registry.npmjs.org/cordova
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/socket.io
npm http request GET https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/socket.io
npm http 200 https://registry.npmjs.org/winston
npm http 200 https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/content-disposition
npm http request GET https://registry.npmjs.org/cookie
npm http request GET https://registry.npmjs.org/cookie-signature
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/array-flatten
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/escape-html
npm http request GET https://registry.npmjs.org/etag
npm http request GET https://registry.npmjs.org/methods
npm http request GET https://registry.npmjs.org/merge-descriptors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/parseurl
npm http request GET https://registry.npmjs.org/range-parser
npm http request GET https://registry.npmjs.org/finalhandler
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/proxy-addr
npm http request GET https://registry.npmjs.org/path-to-regexp
npm http request GET https://registry.npmjs.org/vary
npm http request GET https://registry.npmjs.org/fresh
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/send
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/unpipe
npm http request GET https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ee-first
npm http request GET https://registry.npmjs.org/forwarded
npm http request GET https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http request GET https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/statuses
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/media-typer
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/bluebird
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
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http request GET https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/brace-expansion
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/through
npm http request GET https://registry.npmjs.org/base62
npm http request GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/source-map
npm http request GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/amdefine
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/engine.io
npm http request GET https://registry.npmjs.org/socket.io-parser
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/socket.io-adapter
npm http request GET https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/engine.io
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/socket.io-adapter
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/has-binary
npm http request GET https://registry.npmjs.org/base64id
npm http request GET https://registry.npmjs.org/accepts
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/base64id
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 200 https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/mime-types
npm http request GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime-db
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/component-emitter
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/indexof
npm http request GET https://registry.npmjs.org/object-component
npm http request GET https://registry.npmjs.org/component-bind
npm http request GET https://registry.npmjs.org/backo2
npm http request GET https://registry.npmjs.org/to-array
npm http request GET https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/engine.io-client
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/stack-trace
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/colors
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/jsonify
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/deep-equal
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/winston
npm http request GET https://registry.npmjs.org/javascript-state-machine
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/javascript-state-machine
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/content-type
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/depd
npm http request GET https://registry.npmjs.org/http-errors
npm http request GET https://registry.npmjs.org/on-finished
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/type-is
npm http request GET https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/iconv-lite
npm http request GET https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/iconv-lite
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
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/send
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/esprima-fb
npm http request GET https://registry.npmjs.org/jstransform
npm http request GET https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/jstransform
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
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
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
npm http request GET https://registry.npmjs.org/aws4
npm http request GET https://registry.npmjs.org/bl
npm http request GET https://registry.npmjs.org/caseless
npm http request GET https://registry.npmjs.org/combined-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/forever-agent
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/har-validator
npm http request GET https://registry.npmjs.org/isstream
npm http request GET https://registry.npmjs.org/hawk
npm http request GET https://registry.npmjs.org/http-signature
npm http request GET https://registry.npmjs.org/oauth-sign
npm http request GET https://registry.npmjs.org/json-stringify-safe
npm http request GET https://registry.npmjs.org/is-typedarray
npm http request GET https://registry.npmjs.org/stringstream
npm http request GET https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/tunnel-agent
npm http request GET https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
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
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/color-convert
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
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
npm http request GET https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/boom
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/cycle
npm http request GET https://registry.npmjs.org/eyes
npm http request GET https://registry.npmjs.org/pkginfo
npm http request GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/pkginfo
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/colors
npm http request GET https://registry.npmjs.org/jsdoc
npm http 200 https://registry.npmjs.org/jsdoc
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/underscore
npm http request GET https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/marked
npm http request GET https://registry.npmjs.org/requizzle
npm http request GET https://registry.npmjs.org/wrench
npm http request GET https://registry.npmjs.org/catharsis
npm http request GET https://registry.npmjs.org/js2xmlparser
npm http request GET https://registry.npmjs.org/espree
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/catharsis
npm http 304 https://registry.npmjs.org/requizzle
npm http 304 https://registry.npmjs.org/espree
npm http 304 https://registry.npmjs.org/js2xmlparser
npm http 200 https://registry.npmjs.org/wrench
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/underscore-contrib
npm WARN prefer global marked@0.3.5 should be installed with -g
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/jxc
npm http request GET https://registry.npmjs.org/unzip
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/jxc
npm http 304 https://registry.npmjs.org/unzip
npm http request GET https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/inherits
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/inflight
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
npm http request GET https://registry.npmjs.org/progress
npm http request GET https://registry.npmjs.org/adm-zip
npm http 304 https://registry.npmjs.org/progress
npm http 304 https://registry.npmjs.org/adm-zip
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/inline-process-browser
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
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/foreach
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
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/ast-types
npm http request GET https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
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
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http request GET https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http 304 https://registry.npmjs.org/yallist
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
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/color-convert
npm http request GET https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/ansi-regex
npm http request GET https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http request GET https://registry.npmjs.org/generate-function
npm http request GET https://registry.npmjs.org/generate-object-property
npm http request GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
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
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/cryptiles
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/jsbn
npm http request GET https://registry.npmjs.org/tweetnacl
npm http request GET https://registry.npmjs.org/jodid25519
npm http request GET https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/jodid25519
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/jsbn
npm http 304 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/ecc-jsbn
npm http 304 https://registry.npmjs.org/dashdash
npm http request GET https://registry.npmjs.org/fstream
npm http request GET https://registry.npmjs.org/pullstream
npm http request GET https://registry.npmjs.org/binary
npm http request GET https://registry.npmjs.org/match-stream
npm http request GET https://registry.npmjs.org/setimmediate
npm http 304 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/pullstream
npm http 304 https://registry.npmjs.org/binary
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/setimmediate
npm http request GET https://registry.npmjs.org/chainsaw
npm http request GET https://registry.npmjs.org/buffers
npm http 304 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/buffers
npm http request GET https://registry.npmjs.org/traverse
npm http 304 https://registry.npmjs.org/traverse
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/graceful-fs
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm http 200 https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/minimist
npm http request GET https://registry.npmjs.org/over
npm http request GET https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/slice-stream
npm http 304 https://registry.npmjs.org/over
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET https://registry.npmjs.org/balanced-match
npm http request GET https://registry.npmjs.org/body-parser
npm http request GET https://registry.npmjs.org/concat-map
npm http request GET https://registry.npmjs.org/express
npm http request GET https://registry.npmjs.org/is-property
npm http request GET https://registry.npmjs.org/fs-extra-promise
npm http request GET https://registry.npmjs.org/bn.js
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/express-pouchdb
npm http request GET https://registry.npmjs.org/long
npm http request GET https://registry.npmjs.org/leveldown-mobile
npm http request GET https://registry.npmjs.org/multiplex
npm http request GET https://registry.npmjs.org/node-uuid
npm http request GET https://registry.npmjs.org/request
npm http request GET https://registry.npmjs.org/socket.io-client
npm http request GET https://registry.npmjs.org/nock
npm http request GET https://registry.npmjs.org/randomstring
npm http request GET https://registry.npmjs.org/request-promise
npm http request GET https://registry.npmjs.org/proxyquire
npm http request GET https://registry.npmjs.org/pouchdb
npm http request GET https://registry.npmjs.org/sinon
npm http request GET https://registry.npmjs.org/tape
npm http request GET https://registry.npmjs.org/urlsafe-base64
npm http request GET https://registry.npmjs.org/supertest
npm http request GET https://registry.npmjs.org/supertest-as-promised
npm http request GET https://registry.npmjs.org/tmp
npm http request GET https://registry.npmjs.org/tape-catch
npm http request GET https://registry.npmjs.org/uuid
npm http request GET https://registry.npmjs.org/wrapping-tape
npm http 304 https://registry.npmjs.org/body-parser
npm http 304 https://registry.npmjs.org/is-property
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 304 https://registry.npmjs.org/long
npm http 304 https://registry.npmjs.org/multiplex
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/node-uuid
npm http 304 https://registry.npmjs.org/leveldown-mobile
npm http 304 https://registry.npmjs.org/request-promise
npm http 304 https://registry.npmjs.org/randomstring
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/express-pouchdb
npm http 304 https://registry.npmjs.org/proxyquire
npm http 304 https://registry.npmjs.org/sinon
npm http 304 https://registry.npmjs.org/tape
npm http 304 https://registry.npmjs.org/supertest
npm http 304 https://registry.npmjs.org/supertest-as-promised
npm http 304 https://registry.npmjs.org/tmp
npm http 304 https://registry.npmjs.org/tape-catch
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 304 https://registry.npmjs.org/uuid
npm http 304 https://registry.npmjs.org/pouchdb
npm http 200 https://registry.npmjs.org/nock
npm http 304 https://registry.npmjs.org/wrapping-tape
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
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
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
npm http request GET https://registry.npmjs.org/utils-merge
npm http request GET https://registry.npmjs.org/serve-static
npm http request GET https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/path-to-regexp
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
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/destroy
npm http request GET https://registry.npmjs.org/bluebird
npm http request GET https://registry.npmjs.org/basic-auth
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/pouchdb-all-dbs
npm http request GET https://registry.npmjs.org/header-case-normalizer
npm http request GET https://registry.npmjs.org/compression
npm http request GET https://registry.npmjs.org/cookie-parser
npm http request GET https://registry.npmjs.org/pouchdb-rewrite
npm http request GET https://registry.npmjs.org/pouchdb-find
npm http request GET https://registry.npmjs.org/pouchdb-security
npm http request GET https://registry.npmjs.org/pouchdb-replicator
npm http request GET https://registry.npmjs.org/pouchdb-list
npm http request GET https://registry.npmjs.org/pouchdb-auth
npm http request GET https://registry.npmjs.org/multiparty
npm http request GET https://registry.npmjs.org/pouchdb-update
npm http request GET https://registry.npmjs.org/pouchdb-wrappers
npm http request GET https://registry.npmjs.org/pouchdb-vhost
npm http request GET https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/pouchdb-size
npm http request GET https://registry.npmjs.org/pouchdb-show
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/cookie-parser
npm http 304 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/header-case-normalizer
npm http 304 https://registry.npmjs.org/pouchdb-find
npm http 304 https://registry.npmjs.org/pouchdb-list
npm http 304 https://registry.npmjs.org/pouchdb-replicator
npm http 304 https://registry.npmjs.org/multiparty
npm http 304 https://registry.npmjs.org/pouchdb-all-dbs
npm http 304 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/pouchdb-security
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http fetch GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.0.1.tgz
npm http 304 https://registry.npmjs.org/pouchdb-size
npm http 304 https://registry.npmjs.org/pouchdb-update
npm http 304 https://registry.npmjs.org/pouchdb-wrappers
npm http 304 https://registry.npmjs.org/pouchdb-show
npm http fetch 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-2.0.1.tgz
npm http 304 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/pouchdb-validation
npm http request GET https://registry.npmjs.org/on-headers
npm http request GET https://registry.npmjs.org/compressible
npm http 304 https://registry.npmjs.org/on-headers
npm http 304 https://registry.npmjs.org/compressible
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/stream-counter
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/stream-counter
npm http request GET https://registry.npmjs.org/core-util-is
npm http request GET https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/lie
npm http request GET https://registry.npmjs.org/argsarray
npm http request GET https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/argsarray
npm http 304 https://registry.npmjs.org/tiny-queue
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
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/inline-process-browser
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http request GET https://registry.npmjs.org/acorn
npm http request GET https://registry.npmjs.org/foreach
npm http request GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http request GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/xtend
npm http request GET https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http request GET https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http request GET https://registry.npmjs.org/base64url
npm http request GET https://registry.npmjs.org/pouchdb-plugin-error
npm http request GET https://registry.npmjs.org/pouchdb-system-db
npm http request GET https://registry.npmjs.org/pouchdb-req-http-query
npm http request GET https://registry.npmjs.org/pouchdb-promise
npm http request GET https://registry.npmjs.org/promise-nodify
npm http request GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http request GET https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/couchdb-calculate-session-id
npm http request GET https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/base64url
npm http 304 https://registry.npmjs.org/pouchdb-system-db
npm http 304 https://registry.npmjs.org/pouchdb-plugin-error
npm http 304 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/pouchdb-req-http-query
npm http 304 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 304 https://registry.npmjs.org/secure-random
npm http 304 https://registry.npmjs.org/couchdb-calculate-session-id
npm http 304 https://registry.npmjs.org/pouchdb-promise
npm http 304 https://registry.npmjs.org/crypto-lite
npm http request GET https://registry.npmjs.org/meow
npm http request GET https://registry.npmjs.org/concat-stream
npm http 304 https://registry.npmjs.org/meow
npm http 200 https://registry.npmjs.org/concat-stream
npm http request GET https://registry.npmjs.org/typedarray
npm http 304 https://registry.npmjs.org/typedarray
npm http request GET https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/camelcase-keys
npm http request GET https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/camelcase-keys
npm http 304 https://registry.npmjs.org/object-assign
npm http 304 https://registry.npmjs.org/indent-string
npm http request GET https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/camelcase
npm http 304 https://registry.npmjs.org/map-obj
npm http request GET https://registry.npmjs.org/repeating
npm http request GET https://registry.npmjs.org/get-stdin
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
npm http request GET https://registry.npmjs.org/scope-eval
npm http request GET https://registry.npmjs.org/levelup
npm http request GET https://registry.npmjs.org/pouchdb-collections
npm http request GET https://registry.npmjs.org/pouchdb-collate
npm http request GET https://registry.npmjs.org/memdown
npm http request GET https://registry.npmjs.org/es3ify
npm http request GET https://registry.npmjs.org/localstorage-down
npm http request GET https://registry.npmjs.org/level-write-stream
npm http request GET https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/sublevel-pouchdb
npm http request GET https://registry.npmjs.org/vuvuzela
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/websql
npm http 304 https://registry.npmjs.org/double-ended-queue
npm http 304 https://registry.npmjs.org/levelup
npm http 304 https://registry.npmjs.org/pouchdb-collections
npm http 304 https://registry.npmjs.org/scope-eval
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http 304 https://registry.npmjs.org/memdown
npm http 304 https://registry.npmjs.org/localstorage-down
npm http 304 https://registry.npmjs.org/sublevel-pouchdb
npm http 304 https://registry.npmjs.org/level-write-stream
npm http 304 https://registry.npmjs.org/fruitdown
npm http 304 https://registry.npmjs.org/vuvuzela
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/websql
npm http 304 https://registry.npmjs.org/js-extend
npm http request GET https://registry.npmjs.org/esprima
npm http 304 https://registry.npmjs.org/esprima
npm http request GET https://registry.npmjs.org/tiny-queue
npm http request GET https://registry.npmjs.org/d64
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http 304 https://registry.npmjs.org/d64
npm http 304 https://registry.npmjs.org/tiny-queue
npm http 304 https://registry.npmjs.org/abstract-leveldown
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
npm http 304 https://registry.npmjs.org/deferred-leveldown
npm http 304 https://registry.npmjs.org/level-codec
npm http 200 https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/level-errors
npm http 304 https://registry.npmjs.org/level-iterator-stream
npm http request GET https://registry.npmjs.org/errno
npm http 304 https://registry.npmjs.org/errno
npm http request GET https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http request GET https://registry.npmjs.org/humble-localstorage
npm http 304 https://registry.npmjs.org/humble-localstorage
npm http request GET https://registry.npmjs.org/localstorage-memory
npm http request GET https://registry.npmjs.org/has-localstorage
npm http 304 https://registry.npmjs.org/localstorage-memory
npm http 304 https://registry.npmjs.org/has-localstorage
npm http request GET https://registry.npmjs.org/ltgt
npm http request GET https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/functional-red-black-tree
npm http 304 https://registry.npmjs.org/ltgt
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
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/lru-cache
npm http fetch GET https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.1.tgz
npm http fetch 200 https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.1.tgz
npm http request GET https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http request GET https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/util-deprecate
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http request GET https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/delayed-stream
npm http request GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/async
npm http request GET https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/commander
npm http request GET https://registry.npmjs.org/is-my-json-valid
npm http request GET https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/chalk
npm http request GET https://registry.npmjs.org/ansi-styles
npm http request GET https://registry.npmjs.org/escape-string-regexp
npm http request GET https://registry.npmjs.org/has-ansi
npm http request GET https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http request GET https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/color-convert
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
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/sntp
npm http request GET https://registry.npmjs.org/assert-plus
npm http request GET https://registry.npmjs.org/jsprim
npm http request GET https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/sshpk
npm http request GET https://registry.npmjs.org/extsprintf
npm http request GET https://registry.npmjs.org/json-schema
npm http request GET https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/verror
npm http request GET https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/pull-stream
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/pull-stream
npm http request GET https://registry.npmjs.org/pull-core
npm http 304 https://registry.npmjs.org/pull-core
npm http request GET https://registry.npmjs.org/immediate
npm http request GET https://registry.npmjs.org/noop-fn
npm http request GET https://registry.npmjs.org/sqlite3
npm http 304 https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/sqlite3
npm http fetch GET https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.2.tgz
npm http 304 https://registry.npmjs.org/noop-fn
npm http fetch 200 https://registry.npmjs.org/sqlite3/-/sqlite3-3.1.2.tgz
npm http request GET https://registry.npmjs.org/nan
npm http 304 https://registry.npmjs.org/nan
npm http fetch GET https://registry.npmjs.org/nan/-/nan-2.2.0.tgz
npm http fetch 200 https://registry.npmjs.org/nan/-/nan-2.2.0.tgz
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
npm http request GET https://registry.npmjs.org/random-uuid-v4
npm http request GET https://registry.npmjs.org/couchdb-eval
npm http 304 https://registry.npmjs.org/couchdb-objects
npm http 304 https://registry.npmjs.org/random-uuid-v4
npm http 304 https://registry.npmjs.org/couchdb-eval
npm http request GET https://registry.npmjs.org/is-empty
npm http 304 https://registry.npmjs.org/is-empty
npm http request GET https://registry.npmjs.org/spark-md5
npm http request GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http request GET https://registry.npmjs.org/pouchdb-upsert
npm http request GET https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/spark-md5
npm http 304 https://registry.npmjs.org/jshint
npm http 304 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http 304 https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/pouchdb-extend
npm http request GET https://registry.npmjs.org/minimatch
npm http request GET https://registry.npmjs.org/console-browserify
npm http request GET https://registry.npmjs.org/htmlparser2
npm http request GET https://registry.npmjs.org/cli
npm http request GET https://registry.npmjs.org/exit
npm http request GET https://registry.npmjs.org/strip-json-comments
npm http request GET https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/htmlparser2
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/exit
npm http 304 https://registry.npmjs.org/cli
npm http 200 https://registry.npmjs.org/lodash
npm http 200 https://registry.npmjs.org/shelljs
npm http request GET https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/lru-cache
npm http request GET https://registry.npmjs.org/sigmund
npm http 304 https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/sigmund
npm http request GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/date-now
npm http request GET https://registry.npmjs.org/domhandler
npm http request GET https://registry.npmjs.org/domelementtype
npm http request GET https://registry.npmjs.org/domutils
npm http request GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domelementtype
npm http 304 https://registry.npmjs.org/domhandler
npm http 304 https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/domutils
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
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/bytes
npm http request GET https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/fs-extra
npm http request GET https://registry.npmjs.org/graceful-fs
npm http request GET https://registry.npmjs.org/jsonfile
npm http request GET https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http request GET https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http request GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/wrappy
npm http request GET https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/fast-future
npm http request GET https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/bindings
npm http 304 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http request GET https://registry.npmjs.org/duplexify
npm http request GET https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/varint
npm http request GET https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/end-of-stream
npm http request GET https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/isarray
npm http request GET https://registry.npmjs.org/deep-equal
npm http request GET https://registry.npmjs.org/mkdirp
npm http request GET https://registry.npmjs.org/debug
npm http request GET https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/lodash
npm http request GET https://registry.npmjs.org/propagate
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/lodash
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http 304 https://registry.npmjs.org/propagate
npm http 200 https://registry.npmjs.org/chai
npm http request GET https://registry.npmjs.org/assertion-error
npm http request GET https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/type-detect
npm http 304 https://registry.npmjs.org/assertion-error
npm http 304 https://registry.npmjs.org/deep-eql
npm http request GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ms
npm http request GET https://registry.npmjs.org/ip
npm http 304 https://registry.npmjs.org/ip
npm http request GET https://registry.npmjs.org/module-not-found-error
npm http request GET https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/module-not-found-error
npm http 304 https://registry.npmjs.org/fill-keys
npm http request GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/is-object
npm http request GET https://registry.npmjs.org/array-uniq
npm http 304 https://registry.npmjs.org/array-uniq
npm http request GET https://registry.npmjs.org/util
npm http request GET https://registry.npmjs.org/lolex
npm http request GET https://registry.npmjs.org/formatio
npm http request GET https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/util
npm http 304 https://registry.npmjs.org/samsam
npm http 304 https://registry.npmjs.org/lolex
npm http 304 https://registry.npmjs.org/formatio
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
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/object-component
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/parseuri
npm http request GET https://registry.npmjs.org/has-cors
npm http request GET https://registry.npmjs.org/ws
npm http request GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http request GET https://registry.npmjs.org/parsejson
npm http request GET https://registry.npmjs.org/engine.io-parser
npm http request GET https://registry.npmjs.org/parseqs
npm http request GET https://registry.npmjs.org/component-inherit
npm http request GET https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/yeast
npm http request GET https://registry.npmjs.org/after
npm http request GET https://registry.npmjs.org/base64-arraybuffer
npm http request GET https://registry.npmjs.org/arraybuffer.slice
npm http request GET https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/blob
npm http request GET https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/better-assert
npm http request GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/callsite
npm http request GET https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/ultron
npm http 304 https://registry.npmjs.org/options
npm http request GET https://registry.npmjs.org/json3
npm http request GET https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/benchmark
npm http request GET https://registry.npmjs.org/superagent
npm http 200 https://registry.npmjs.org/superagent
npm http fetch GET https://registry.npmjs.org/superagent/-/superagent-1.8.2.tgz
npm http fetch 200 https://registry.npmjs.org/superagent/-/superagent-1.8.2.tgz
npm http request GET https://registry.npmjs.org/qs
npm http request GET https://registry.npmjs.org/form-data
npm http request GET https://registry.npmjs.org/readable-stream
npm http request GET https://registry.npmjs.org/extend
npm http request GET https://registry.npmjs.org/reduce-component
npm http request GET https://registry.npmjs.org/cookiejar
npm http request GET https://registry.npmjs.org/formidable
npm http 304 https://registry.npmjs.org/reduce-component
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/cookiejar
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/formidable
npm http request GET https://registry.npmjs.org/defined
npm http request GET https://registry.npmjs.org/function-bind
npm http request GET https://registry.npmjs.org/object-inspect
npm http request GET https://registry.npmjs.org/glob
npm http request GET https://registry.npmjs.org/has
npm http request GET https://registry.npmjs.org/string.prototype.trim
npm http request GET https://registry.npmjs.org/resumer
npm http request GET https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/has
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/resumer
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/string.prototype.trim
npm http request GET https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/es-abstract
npm http request GET https://registry.npmjs.org/is-regex
npm http request GET https://registry.npmjs.org/es-to-primitive
npm http request GET https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/es-to-primitive
npm http 304 https://registry.npmjs.org/is-regex
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
