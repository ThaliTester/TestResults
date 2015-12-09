#### Test 50650278eab32a5_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/GAv4    ( 2878): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2878): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2878): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2382): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2878): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2878): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2878): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/ActivityManager(  760): Killing 2113:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/System  ( 2878): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2878): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2113/cgroup.procs: No such file or directory
V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1562): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1562): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1562): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 2931): 
D/AndroidRuntime( 2931): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2931): CheckJNI is OFF
D/AndroidRuntime( 2931): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2952 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2931): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/ActivityManager(  760): Killing 2211:com.google.android.youtube/u0a80 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2211/cgroup.procs: No such file or directory
I/WebViewFactory( 2952): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2952): Time to load native libraries: 2 ms (timestamps 6057-6059)
I/LibraryLoader( 2952): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2952): Binding Chromium to main looper Looper (main, tid 1) {25fa637a}
I/LibraryLoader( 2952): Expected native library version number "",actual native library version number ""
I/chromium( 2952): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2952): Initializing chromium process, singleProcess=true
,W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2952): ApplicationContext is null in ApplicationStatus
,W/chromium( 2952): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2952): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2952): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2952): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2952): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2827e3a3:true
,D/BluetoothAdapter( 2952): 357585972: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2952): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2952): CordovaWebView is running on device made by: LGE
,W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2952): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2952): Render dirty regions requested: true
,D/Atlas   ( 2952): Validating map...
,W/chromium( 2952): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2952): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2952): Enabling debug mode 0
,W/BindingManager( 2952): Cannot call determinedVisibility() - never saw a connection for the pid: 2952
,W/IInputConnectionWrapper( 2952): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +511ms (total +54s309ms)
,D/JsMessageQueue( 2952): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2952): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2952): jxcore cordova android initializing
,W/jxcore-log( 2952): Initializing JXcore engine
W/jxcore-log( 2952): JXcore engine is ready
,W/jxcore-log( 2952): Starting JXcore engine
,W/.test.thalitest( 2952): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7889]" dev="sockfs" ino=7889 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2952): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 2952): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8500]" dev="sockfs" ino=8500 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2952): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18867]" dev="sockfs" ino=18867 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2952): Platform android
W/jxcore-log( 2952): 
W/jxcore-log( 2952): Process ARCH arm
W/jxcore-log( 2952): 
,I/jxcore-log( 2952): JXcore Cordova bridge is ready!
I/jxcore-log( 2952): 
W/jxcore-log( 2952): JXcore engine is started
,I/chromium( 2952): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 2952): Error!: missing ) after argument list
E/jxcore  ( 2952): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 2952): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  760): Killing 2302:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2302/cgroup.procs: No such file or directory
W/PluginManager( 2952): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 31ms. Plugin should use CordovaInterface.getThreadPool().
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1413): OkHttp exception
W/EventLoggerService( 1413): Unable to send logs Error code: 262146
,W/Search.LoginHelper( 1413): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1346): Explicit concurrent mark sweep GC freed 11947(705KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 768us total 33.488ms
,W/Search.LoginHelper( 1413): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/Finsky  ( 2382): [231] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2382): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ClearcutLoggerApiImpl( 1368): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1346): disconnect managed GoogleApiClient
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 2351:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2351/cgroup.procs: No such file or directory
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 2443:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty for 1800s
,I/ActivityManager(  760): Killing 1771:com.google.android.apps.fitness/u0a45 (adj 15): empty for 1800s
,I/ProcessStatsService(  760): Prepared write state in 3ms
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2443/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1771/cgroup.procs: No such file or directory
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  760): Explicit concurrent mark sweep GC freed 21482(1128KB) AllocSpace objects, 10(206KB) LOS objects, 33% free, 27MB/41MB, paused 1.169ms total 56.835ms
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1346): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-07.bin
,I/ActivityManager(  760): Killing 2324:com.google.android.gm/u0a70 (adj 15): empty for 1800s
,I/EventLogService( 1562): Aggregate from 1449668397359 (log), 1449668397359 (data)
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2324/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1999:com.google.android.calendar/u0a31 (adj 15): empty for 1800s
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_1999/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2471:com.google.android.music:main/u0a60 (adj 15): empty for 1800s
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2471/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
