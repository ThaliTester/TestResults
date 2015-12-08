#### Test 50650278352fc1f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2884): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2884):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2884):   adb logcat -s GAv4
W/GAv4    ( 2884): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2884): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2884): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2884): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2391): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  762): Killing 2209:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 2884): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2884): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2925): 
D/AndroidRuntime( 2925): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2925): CheckJNI is OFF
D/AndroidRuntime( 2925): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  762): failed to open /acct/uid_10080/pid_2209/cgroup.procs: No such file or directory
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/JNIHelp ( 2884): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2959 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2925): Shutting down VM
W/System  ( 2884): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2884): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  762): Display changed displayId=0
I/Icing   ( 1565): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1565): Loaded CLD2 Version V2.0 - 20141016
I/WebViewFactory( 2959): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1565): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/LibraryLoader( 2959): Time to load native libraries: 1 ms (timestamps 8220-8221)
I/LibraryLoader( 2959): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2959): Binding Chromium to main looper Looper (main, tid 1) {137e1980}
I/LibraryLoader( 2959): Expected native library version number "",actual native library version number ""
I/chromium( 2959): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2959): Initializing chromium process, singleProcess=true
W/art     ( 2959): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2959): ApplicationContext is null in ApplicationStatus
W/chromium( 2959): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2959): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2959): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2959): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2959): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@321d6513:true
D/BluetoothAdapter( 2959): 1014000138: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2959): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2959): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2959): CordovaWebView is running on device made by: LGE
W/art     ( 2959): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2959): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2959): Render dirty regions requested: true
D/Atlas   ( 2959): Validating map...
W/chromium( 2959): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2959): Initialized EGL, version 1.4
D/OpenGLRenderer( 2959): Enabling debug mode 0
I/Keyboard.Facilitator( 1055): onFinishInput()
W/IInputConnectionWrapper( 2959): showStatusIcon on inactive InputConnection
I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +461ms (total +55s593ms)
W/BindingManager( 2959): Cannot call determinedVisibility() - never saw a connection for the pid: 2959
D/JsMessageQueue( 2959): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2959): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2959): jxcore cordova android initializing
I/ActivityManager(  762): Killing 2311:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_2311/cgroup.procs: No such file or directory
,W/jxcore-log( 2959): Initializing JXcore engine
W/jxcore-log( 2959): JXcore engine is ready
,W/jxcore-log( 2959): Starting JXcore engine
,W/.test.thalitest( 2959): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7623]" dev="sockfs" ino=7623 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2959): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2959): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9611]" dev="sockfs" ino=9611 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2959): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17735]" dev="sockfs" ino=17735 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2959): Platform android
W/jxcore-log( 2959): 
W/jxcore-log( 2959): Process ARCH arm
W/jxcore-log( 2959): 
,I/jxcore-log( 2959): JXcore Cordova bridge is ready!
I/jxcore-log( 2959): 
,W/jxcore-log( 2959): JXcore engine is started
,I/Choreographer( 2959): Skipped 109 frames!  The application may be doing too much work on its main thread.
I/chromium( 2959): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 2959): Error!: missing ) after argument list
E/jxcore  ( 2959): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
I/chromium( 2959): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  762): Killing 2360:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10069/pid_2360/cgroup.procs: No such file or directory
,W/PluginManager( 2959): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 179ms. Plugin should use CordovaInterface.getThreadPool().
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1325): Explicit concurrent mark sweep GC freed 11626(695KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 683us total 25.828ms
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1055): run()
I/Keyboard.Facilitator( 1055): flushDynamicLanguageModels()
,I/ConfigService( 1325): onCreate
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,I/ConfigService( 1325): onDestroy
,I/ClearcutLoggerApiImpl( 1282): disconnect managed GoogleApiClient
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,I/art     (  762): Explicit concurrent mark sweep GC freed 19093(905KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.232ms total 59.445ms
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  762): Killing 1775:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_1775/cgroup.procs: No such file or directory
,D/Finsky  ( 2391): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2391): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2391): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2391): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 2391): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 2391): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2391): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1282): client connected with version: 8296000
,D/Finsky  ( 2391): [246] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2391): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Installation state replication failed.
D/Finsky  ( 2391): [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  762): Explicit concurrent mark sweep GC freed 20245(858KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.074ms total 57.240ms
,I/UsageStatsService(  762): User[0] Flushing usage stats to disk
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  762): Killing 2462:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty for 1800s
,I/ProcessStatsService(  762): Prepared write state in 3ms
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2462/cgroup.procs: No such file or directory
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1325): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  762): Pruning old procstats: /data/system/procstats/state-2015-12-07-15-36-07.bin
,I/art     ( 1325): Explicit concurrent mark sweep GC freed 25241(1670KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/32MB, paused 3.117ms total 52.710ms
,I/EventLogService( 1565): Aggregate from 1449588174032 (log), 1449588174032 (data)
,E/DataBuffer( 1325): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1061f7a3)
E/DataBuffer( 1325): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e3c4aa0)
,E/DataBuffer( 1325): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3628b659)
,E/DataBuffer( 1325): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18baf21e)
E/DataBuffer( 1325): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e926aff)
,I/ActivityManager(  762): Killing 2334:com.google.android.gm/u0a70 (adj 15): empty for 1800s
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2334/cgroup.procs: No such file or directory
I/ActivityManager(  762): Killing 2031:com.google.android.calendar/u0a31 (adj 15): empty for 1800s
,W/libprocessgroup(  762): failed to open /acct/uid_10031/pid_2031/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Killing 2487:com.google.android.music:main/u0a60 (adj 15): empty for 1800s
,W/libprocessgroup(  762): failed to open /acct/uid_10060/pid_2487/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
