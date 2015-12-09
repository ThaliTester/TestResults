#### Test 5065027873d6a28_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2463): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2269:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2945): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2945): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2945): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2269/cgroup.procs: No such file or directory
V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1621): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1621): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1621): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 2997): 
D/AndroidRuntime( 2997): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2997): CheckJNI is OFF
D/AndroidRuntime( 2997): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3021 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2997): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/ActivityManager(  761): Killing 2360:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2360/cgroup.procs: No such file or directory
,I/WebViewFactory( 3021): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3021): Time to load native libraries: 2 ms (timestamps 7220-7222)
I/LibraryLoader( 3021): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3021): Binding Chromium to main looper Looper (main, tid 1) {2c106bf}
,I/LibraryLoader( 3021): Expected native library version number "",actual native library version number ""
,I/chromium( 3021): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3021): Initializing chromium process, singleProcess=true
,W/art     ( 3021): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3021): ApplicationContext is null in ApplicationStatus
,W/chromium( 3021): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3021): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3021): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3021): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3021): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c7928f:true
,D/BluetoothAdapter( 3021): 741175734: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3021): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3021): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3021): CordovaWebView is running on device made by: LGE
,W/art     ( 3021): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3021): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3021): Render dirty regions requested: true
,D/Atlas   ( 3021): Validating map...
,W/chromium( 3021): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3021): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3021): Enabling debug mode 0
,W/IInputConnectionWrapper( 3021): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +484ms (total +55s712ms)
,W/BindingManager( 3021): Cannot call determinedVisibility() - never saw a connection for the pid: 3021
,D/JsMessageQueue( 3021): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3021): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 3021): jxcore cordova android initializing
,W/jxcore-log( 3021): Initializing JXcore engine
W/jxcore-log( 3021): JXcore engine is ready
,W/jxcore-log( 3021): Starting JXcore engine
,W/.test.thalitest( 3021): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9408]" dev="sockfs" ino=9408 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3021): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3021): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9479]" dev="sockfs" ino=9479 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3021): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17850]" dev="sockfs" ino=17850 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3021): Platform android
W/jxcore-log( 3021): 
,W/jxcore-log( 3021): Process ARCH arm
W/jxcore-log( 3021): 
,I/jxcore-log( 3021): JXcore Cordova bridge is ready!
I/jxcore-log( 3021): 
,W/jxcore-log( 3021): JXcore engine is started
I/Choreographer( 3021): Skipped 115 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3021): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3021): Error!: missing ) after argument list
E/jxcore  ( 3021): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3021): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  761): Killing 2416:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2416/cgroup.procs: No such file or directory
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1360): OkHttp exception
W/EventLoggerService( 1360): Unable to send logs Error code: 262146
,W/Search.LoginHelper( 1360): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1360): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/Finsky  ( 2463): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2463): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ClearcutLoggerApiImpl( 1471): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1294): disconnect managed GoogleApiClient
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 13886(815KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 740us total 58.611ms
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium(  943): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  943): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  943): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 1818:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1818/cgroup.procs: No such file or directory
,D/Finsky  ( 2463): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2463): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2463): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 20005(945KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 835us total 49.530ms
,W/Finsky  ( 2463): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 2463): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 2463): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2463): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1294): client connected with version: 8296000
,D/Finsky  ( 2463): [251] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2463): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2463): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium(  943): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  943): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  943): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1471): disconnect managed GoogleApiClient,
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 2523:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty for 1800s
,I/ProcessStatsService(  761): Prepared write state in 3ms
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2523/cgroup.procs: No such file or directory
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1471): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  761): Pruning old procstats: /data/system/procstats/state-2015-12-08-07-12-52.bin
,I/EventLogService( 1621): Aggregate from 1449626455069 (log), 1449626455069 (data)
,I/ActivityManager(  761): Killing 2386:com.google.android.gm/u0a70 (adj 15): empty for 1800s
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2386/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2064:com.google.android.calendar/u0a31 (adj 15): empty for 1800s
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_2064/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2552:com.google.android.music:main/u0a60 (adj 15): empty for 1800s
,W/libprocessgroup(  761): failed to open /acct/uid_10060/pid_2552/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
