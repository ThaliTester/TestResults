#### Test 50650278cc6513d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2907): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2907):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2907):   adb logcat -s GAv4
W/GAv4    ( 2907): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2907): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2907): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2907): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2395): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  756): Killing 2135:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 2907): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2907): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2907): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2135/cgroup.procs: No such file or directory
V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1558): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1558): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1558): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 2981): 
D/AndroidRuntime( 2981): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2981): CheckJNI is OFF
D/AndroidRuntime( 2981): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3002 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2981): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/WebViewFactory( 3002): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  756): Killing 2227:com.google.android.youtube/u0a80 (adj 15): empty #17
,I/LibraryLoader( 3002): Time to load native libraries: 3 ms (timestamps 7571-7574)
I/LibraryLoader( 3002): Expected native library version number "",actual native library version number ""
,W/libprocessgroup(  756): failed to open /acct/uid_10080/pid_2227/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 3002): Binding Chromium to main looper Looper (main, tid 1) {2dc2fdba}
I/LibraryLoader( 3002): Expected native library version number "",actual native library version number ""
I/chromium( 3002): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3002): Initializing chromium process, singleProcess=true
W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3002): ApplicationContext is null in ApplicationStatus
,W/chromium( 3002): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3002): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3002): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3002): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3002): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b1a65f:true
,D/BluetoothAdapter( 3002): 477584455: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3002): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3002): CordovaWebView is running on device made by: LGE
,W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3002): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3002): Render dirty regions requested: true
,D/Atlas   ( 3002): Validating map...
,W/chromium( 3002): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3002): Initialized EGL, version 1.4
D/OpenGLRenderer( 3002): Enabling debug mode 0
,I/Keyboard.Facilitator( 1093): onFinishInput()
,W/IInputConnectionWrapper( 3002): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +472ms (total +56s51ms)
,W/BindingManager( 3002): Cannot call determinedVisibility() - never saw a connection for the pid: 3002
,D/JsMessageQueue( 3002): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3002): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1544746880
,D/JX-Cordova( 3002): jxcore cordova android initializing
,W/jxcore-log( 3002): Initializing JXcore engine
W/jxcore-log( 3002): JXcore engine is ready
,W/jxcore-log( 3002): Starting JXcore engine
,W/.test.thalitest( 3002): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9350]" dev="sockfs" ino=9350 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3002): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3002): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6627]" dev="sockfs" ino=6627 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3002): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18956]" dev="sockfs" ino=18956 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3002): Platform android
W/jxcore-log( 3002): 
W/jxcore-log( 3002): Process ARCH arm
W/jxcore-log( 3002): 
,I/jxcore-log( 3002): JXcore Cordova bridge is ready!
I/jxcore-log( 3002): 
W/jxcore-log( 3002): JXcore engine is started
,I/chromium( 3002): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3002): Error!: missing ) after argument list
E/jxcore  ( 3002): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3002): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  756): Killing 2318:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2318/cgroup.procs: No such file or directory
,W/PluginManager( 3002): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1410): OkHttp exception
W/EventLoggerService( 1410): Unable to send logs Error code: 262146
,I/art     ( 1388): Explicit concurrent mark sweep GC freed 11039(658KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 19MB/32MB, paused 740us total 22.463ms
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1093): run()
I/Keyboard.Facilitator( 1093): flushDynamicLanguageModels()
,I/ConfigService( 1388): onCreate
,I/ConfigService( 1388): onDestroy
,I/ClearcutLoggerApiImpl( 1288): disconnect managed GoogleApiClient
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  756): Explicit concurrent mark sweep GC freed 19037(882KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.024ms total 51.350ms
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication failed.
,D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2395): [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1388): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }

```
