#### Test (Fail) 84500654 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   8046b77..833e1a9  vNext_aaladev_959 -> origin/vNext_aaladev_959

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_evabishchevich_848 set up to track remote branch vNext_evabishchevich_848 from origin.
Already up-to-date.

Already on 'master'
Switched to a new branch 'vNext_evabishchevich_848'
Note: checking out '833e1a9'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 833e1a9... cosmetics

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
├── bluebird@3.4.6 
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
│   ├── graceful-fs@4.1.6 
│   ├── jsonfile@2.3.1 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.0.6 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.0 
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

-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/bluebird
npm http fetch GET http://192.168.1.100:4873/bluebird/-/bluebird-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/express
npm http fetch 200 http://192.168.1.100:4873/bluebird/-/bluebird-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/negotiator
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
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http fetch GET http://192.168.1.100:4873/inherits/-/inherits-2.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/inherits/-/inherits-2.0.3.tgz
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http fetch GET http://192.168.1.100:4873/bluebird/-/bluebird-2.11.0.tgz
npm http fetch 200 http://192.168.1.100:4873/bluebird/-/bluebird-2.11.0.tgz
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/rimraf
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.6.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.6.tgz
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http fetch GET http://192.168.1.100:4873/glob/-/glob-7.0.6.tgz
npm http fetch 200 http://192.168.1.100:4873/glob/-/glob-7.0.6.tgz
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/minimatch
npm http fetch GET http://192.168.1.100:4873/once/-/once-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/once/-/once-1.4.0.tgz
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parsejson
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
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
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jsonify
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/through
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

module.js:802
    throw err;
          ^
Error: Cannot find module 'lie'
    at Function.Module._oldRes (module.js:800:15)
    at Function.Module._resolveFilename (module.js:1768:19)
    at Function.Module._load (module.js:360:25)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/IPAddressToFile.js:6:15)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/generateServerAddress.js:3:23)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)

```

Error: Command failed: npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/bluebird
npm http fetch GET http://192.168.1.100:4873/bluebird/-/bluebird-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/express
npm http fetch 200 http://192.168.1.100:4873/bluebird/-/bluebird-3.4.6.tgz
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/negotiator
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
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http fetch GET http://192.168.1.100:4873/inherits/-/inherits-2.0.3.tgz
npm http fetch 200 http://192.168.1.100:4873/inherits/-/inherits-2.0.3.tgz
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http fetch GET http://192.168.1.100:4873/bluebird/-/bluebird-2.11.0.tgz
npm http fetch 200 http://192.168.1.100:4873/bluebird/-/bluebird-2.11.0.tgz
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/rimraf
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.6.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.6.tgz
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http fetch GET http://192.168.1.100:4873/glob/-/glob-7.0.6.tgz
npm http fetch 200 http://192.168.1.100:4873/glob/-/glob-7.0.6.tgz
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/once
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/minimatch
npm http fetch GET http://192.168.1.100:4873/once/-/once-1.4.0.tgz
npm http fetch 200 http://192.168.1.100:4873/once/-/once-1.4.0.tgz
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/balanced-match
npm http 200 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/has-binary-data
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/has-binary-data
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/after
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bufferutil
npm http request GET http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/utf-8-validate
npm http 200 http://192.168.1.100:4873/bufferutil
npm http 200 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/nan
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/object-keys
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http fetch GET https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/parsejson
npm http fetch 200 https://github.com/rase-/node-XMLHttpRequest/archive/a6b6f2.tar.gz
npm http fetch GET https://github.com/component/global/archive/v2.0.1.tar.gz
npm http fetch 200 https://github.com/component/global/archive/v2.0.1.tar.gz
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
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/jsonify
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jsonify
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/through
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

module.js:802
    throw err;
          ^
Error: Cannot find module 'lie'
    at Function.Module._oldRes (module.js:800:15)
    at Function.Module._resolveFilename (module.js:1768:19)
    at Function.Module._load (module.js:360:25)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/IPAddressToFile.js:6:15)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
    at Function.Module._load (module.js:405:12)
    at Module.require (module.js:475:17)
    at require (module.js:493:17)
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/TestServer/generateServerAddress.js:3:23)
    at Module._compile (module.js:619:26)
    at Object.Module._extensions..js (module.js:649:10)
    at Module.load (module.js:440:36)
