#### Test (Fail) 80807573 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   fdd3b64..2f454a1  vNext_artemjackson_758 -> origin/vNext_artemjackson_758

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '2f454a1'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 2f454a1... Removed additional registries

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
├── global@2.0.1 
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
├─┬ winston@2.2.0 
│ ├── async@1.0.0 
│ ├── colors@1.0.3 
│ ├── cycle@1.0.3 
│ ├── eyes@0.1.8 
│ ├── isstream@0.1.2 
│ ├── pkginfo@0.3.1 
│ └── stack-trace@0.0.9 
└── xmlhttprequest@1.5.0 

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/global
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/global
npm http fetch GET http://192.168.1.100:4873/global/-/global-2.0.1.tgz
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/jsonify
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/mime-db
npm http 200 http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/negotiator
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http fetch GET http://192.168.1.100:4873/xmlhttprequest/-/xmlhttprequest-1.5.0.tgz
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/ms
npm http fetch 200 http://192.168.1.100:4873/global/-/global-2.0.1.tgz
npm http 200 http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/source-map
npm http fetch 200 http://192.168.1.100:4873/xmlhttprequest/-/xmlhttprequest-1.5.0.tgz
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
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
npm http request GET http://192.168.1.100:4873/node-ssdp
npm http request GET http://192.168.1.100:4873/taffydb
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/taffydb
npm http 200 http://192.168.1.100:4873/node-ssdp
npm http fetch GET http://192.168.1.100:4873/node-ssdp/-/node-ssdp-2.6.5.tgz
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/marked
npm http 304 http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/underscore
npm http 304 http://192.168.1.100:4873/salti
npm http 304 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http fetch 200 http://192.168.1.100:4873/node-ssdp/-/node-ssdp-2.6.5.tgz
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/varint
npm ERR! Darwin 15.6.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "--loglevel" "http" "--color" "true" "install" "--no-optional" "--build-from-source"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12

npm ERR! No compatible version found: taffydb@2.6.2
npm ERR! Valid install targets:
npm ERR! 2.7.2, 0.0.1
npm ERR! 
npm ERR! 
npm ERR! If you need help, you may report this error at:
npm ERR!     <https://github.com/npm/npm/issues>

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/Thali_CordovaPlugin/thali/npm-debug.log

```

Error: Command failed: npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/global
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/nan
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/acorn
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/async
npm http 200 http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/bindings
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/global
npm http fetch GET http://192.168.1.100:4873/global/-/global-2.0.1.tgz
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/jsonify
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/mime-db
npm http 200 http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/negotiator
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/serve-static
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http fetch GET http://192.168.1.100:4873/xmlhttprequest/-/xmlhttprequest-1.5.0.tgz
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/ms
npm http fetch 200 http://192.168.1.100:4873/global/-/global-2.0.1.tgz
npm http 200 http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/source-map
npm http fetch 200 http://192.168.1.100:4873/xmlhttprequest/-/xmlhttprequest-1.5.0.tgz
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
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
npm http request GET http://192.168.1.100:4873/node-ssdp
npm http request GET http://192.168.1.100:4873/taffydb
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/salti
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/taffydb
npm http 200 http://192.168.1.100:4873/node-ssdp
npm http fetch GET http://192.168.1.100:4873/node-ssdp/-/node-ssdp-2.6.5.tgz
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/commander
npm http 304 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/catharsis
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/chalk
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/express
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/forwarded
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/foreach
npm http 304 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/recast
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/marked
npm http 304 http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/raw-body
npm http 200 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/requizzle
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/underscore
npm http 304 http://192.168.1.100:4873/salti
npm http 304 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/winston
npm http 304 http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http fetch 200 http://192.168.1.100:4873/node-ssdp/-/node-ssdp-2.6.5.tgz
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/wrench
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/varint
npm ERR! Darwin 15.6.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "--loglevel" "http" "--color" "true" "install" "--no-optional" "--build-from-source"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12

npm ERR! No compatible version found: taffydb@2.6.2
npm ERR! Valid install targets:
npm ERR! 2.7.2, 0.0.1
npm ERR! 
npm ERR! 
npm ERR! If you need help, you may report this error at:
npm ERR!     <https://github.com/npm/npm/issues>

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/Thali_CordovaPlugin/thali/npm-debug.log
