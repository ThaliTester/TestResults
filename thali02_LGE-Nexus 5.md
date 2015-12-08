#### Test 5065027865f659b_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2898): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2898):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2898):   adb logcat -s GAv4
W/GAv4    ( 2898): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2898): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2898): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2898): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2439): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2898): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2898): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 2898): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/ActivityManager(  760): Killing 2264:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 2898): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2898): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2947): 
D/AndroidRuntime( 2947): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2947): CheckJNI is OFF
W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2264/cgroup.procs: No such file or directory
V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2947): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2971 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2947): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/Icing   ( 1626): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Icing   ( 1626): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1626): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/WebViewFactory( 2971): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2971): Time to load native libraries: 3 ms (timestamps 5778-5781)
I/LibraryLoader( 2971): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2971): Binding Chromium to main looper Looper (main, tid 1) {24f8df18}
,I/LibraryLoader( 2971): Expected native library version number "",actual native library version number ""
,I/chromium( 2971): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2971): Initializing chromium process, singleProcess=true
,W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2971): ApplicationContext is null in ApplicationStatus
,W/chromium( 2971): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2971): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2971): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2971): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2971): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c60c973:true
,D/BluetoothAdapter( 2971): 211895010: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2971): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2971): CordovaWebView is running on device made by: LGE
,W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2971): Render dirty regions requested: true
,D/Atlas   ( 2971): Validating map...
,W/chromium( 2971): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2971): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2971): Enabling debug mode 0
,W/IInputConnectionWrapper( 2971): showStatusIcon on inactive InputConnection
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +455ms (total +52s966ms)
W/BindingManager( 2971): Cannot call determinedVisibility() - never saw a connection for the pid: 2971
D/JsMessageQueue( 2971): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2971): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2971): jxcore cordova android initializing
I/ActivityManager(  760): Killing 2356:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2356/cgroup.procs: No such file or directory
,W/jxcore-log( 2971): Initializing JXcore engine
W/jxcore-log( 2971): JXcore engine is ready
,W/jxcore-log( 2971): Starting JXcore engine
,W/.test.thalitest( 2971): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8075]" dev="sockfs" ino=8075 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2971): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2971): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6426]" dev="sockfs" ino=6426 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2971): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17196]" dev="sockfs" ino=17196 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2971): Platform android
W/jxcore-log( 2971): 
,W/jxcore-log( 2971): Process ARCH arm
W/jxcore-log( 2971): 
,I/jxcore-log( 2971): JXcore Cordova bridge is ready!
I/jxcore-log( 2971): 
,W/jxcore-log( 2971): JXcore engine is started
I/chromium( 2971): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 2971): Error!: missing ) after argument list
E/jxcore  ( 2971): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 2971): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  760): Killing 2406:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/PluginManager( 2971): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2406/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1832:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1832/cgroup.procs: No such file or directory
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1335): OkHttp exception
W/EventLoggerService( 1335): Unable to send logs Error code: 262146
,D/Finsky  ( 2439): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2439): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ClearcutLoggerApiImpl( 1311): disconnect managed GoogleApiClient
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3086
W/ProcessCpuTracker(  760): Skipping unknown process pid 3093
W/ProcessCpuTracker(  760): Skipping unknown process pid 3094
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1377): Explicit concurrent mark sweep GC freed 12411(729KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 791us total 31.370ms
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 2486:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty for 1800s
,I/ProcessStatsService(  760): Prepared write state in 3ms
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2486/cgroup.procs: No such file or directory
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  760): Explicit concurrent mark sweep GC freed 20436(1069KB) AllocSpace objects, 10(206KB) LOS objects, 33% free, 27MB/41MB, paused 999us total 67.367ms
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1377): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-12-24.bin
,I/EventLogService( 1626): Aggregate from 1449597601659 (log), 1449597601659 (data)
,I/ActivityManager(  760): Killing 2508:com.google.android.music:main/u0a60 (adj 13): empty for 1800s
,I/ActivityManager(  760): Killing 2084:com.google.android.calendar/u0a31 (adj 13): empty for 1804s
,I/ActivityManager(  760): Killing 2378:com.google.android.gm/u0a70 (adj 15): empty for 1804s
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2508/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_2084/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2378/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
