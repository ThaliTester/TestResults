#### Test 50650278b1aec71_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1547): Explicit concurrent mark sweep GC freed 27213(1460KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.330ms total 58.412ms
D/Finsky  ( 2729): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2729): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2729): [1] 5.onFinished: Scheduling replication attempt 4.
D/AndroidRuntime( 3190): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3190): CheckJNI is OFF
D/AndroidRuntime( 3190): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{91fca7c token=Token{207e5d6f ActivityRecord{54e684e u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3190): Shutting down VM
V/WindowManager(  821): Adding window Window{172cb681 u0 Starting com.test.thalitest} at 3 of 8 (after Window{2a23aaa5 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1520): mic_close com.google.android.apps.gsa.speech.audio.u@10d8096d
I/HotwordDetector( 1520): Closing mic
I/ActivityManager(  821): Start proc 3205:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1520): Stopping hotword detection.
I/HotwordRecognitionRnr( 1520): Hotword detection finished
W/GCoreFlp( 1762): No location to return for getLastLocation()
I/ActivityManager(  821): Killing 2688:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702020371
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/ActivityManager(  821): Killing 2767:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/WebViewFactory( 3205): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3205): Time to load native libraries: 4 ms (timestamps 8368-8372)
I/LibraryLoader( 3205): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3205): Binding Chromium to main looper Looper (main, tid 1) {23bb9f28}
,I/LibraryLoader( 3205): Expected native library version number "",actual native library version number ""
I/chromium( 3205): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3205): Initializing chromium process, singleProcess=true
W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3205): ApplicationContext is null in ApplicationStatus
,W/chromium( 3205): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3205): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 3205): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3205): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3205): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/art     (  821): Explicit concurrent mark sweep GC freed 19524(930KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.214ms total 85.015ms
D/BluetoothManagerService(  821): Message: 20
,D/BluetoothAdapter( 3205): 825849539: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8f41f1:true
,W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3205): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3205): CordovaWebView is running on device made by: motorola
,W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3205): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3205): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3205): Validating map...
,V/WindowManager(  821): Adding window Window{26238961 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{172cb681 u0 Starting com.test.thalitest})
,W/chromium( 3205): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3205): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3205): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +1s256ms (total +2m6s186ms),
,I/Keyboard.Facilitator( 1239): onFinishInput(),
,W/BindingManager( 3205): Cannot call determinedVisibility() - never saw a connection for the pid: 3205
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
,I/kickstart(  872): STATUS: 950272 bytes transferred in 0.983504 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,D/JsMessageQueue( 3205): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3205): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576193152
,D/JX-Cordova( 3205): jxcore cordova android initializing
,W/jxcore-log( 3205): Initializing JXcore engine
W/jxcore-log( 3205): JXcore engine is ready
,W/jxcore-log( 3205): Starting JXcore engine
,W/.test.thalitest( 3205): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13166]" dev="sockfs" ino=13166 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3205): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3205): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13296]" dev="sockfs" ino=13296 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3205): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19391]" dev="sockfs" ino=19391 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3205): Platform android,
W/jxcore-log( 3205): 
,W/jxcore-log( 3205): Process ARCH arm
W/jxcore-log( 3205): ,
,I/jxcore-log( 3205): JXcore Cordova bridge is ready!
I/jxcore-log( 3205): 
,W/jxcore-log( 3205): JXcore engine is started
I/Choreographer( 3205): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3205): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3205): Error!: missing ) after argument list
E/jxcore  ( 3205): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3205): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (185 us)
,W/PluginManager( 3205): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 54ms. Plugin should use CordovaInterface.getThreadPool().
,W/IInputConnectionWrapper( 3205): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1239): onFinishInput()
,W/LocationOracleImpl( 1520): Best location was null
,W/ErrorReporter( 1520): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1520): Starting hotword detection.
,W/GCoreFlp( 1762): No location to return for getLastLocation()
,I/MicrophoneInputStream( 1520): mic_starting com.google.android.apps.gsa.speech.audio.u@355c0ae9
,I/AudioFlinger(  359): AudioFlinger's thread 0xb4d9f000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1520): mic_started com.google.android.apps.gsa.speech.audio.u@355c0ae9
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1762): No location to return for getLastLocation()
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702020371
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/HotwordWorker( 1520): onReady
,W/OpenGLRenderer( 1333): Incorrectly called buildLayer on View: ew, destroying layer...
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ResourceType( 1073): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1073): Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  821): Display changed displayId=0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0,
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 258ms
,I/DreamManagerService(  821): Entering dreamland.
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,E/wifi    (  821): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
,I/PowerManagerService(  821): Dozing...
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,I/Keyboard.Facilitator( 1239): onFinishInput()
,E/wifi    (  821): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/WifiStateMachine(  821): cancelDelayedScan -> 2
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2729): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2729): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2729): [1] 5.onFinished: Scheduling replication attempt 5.
,I/EventLogService( 1792): Opted in for usage reporting
I/EventLogService( 1792): Aggregate from 1449593940798 (log), 1449593940798 (data)
,W/EventLogAggregator( 1792): Unknown tag: snet_gcore
W/EventLogAggregator( 1792): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1792): dumping service [account]
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2729): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2729): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2729): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1239): run()
I/Keyboard.Facilitator( 1239): flushDynamicLanguageModels()
,I/ConfigService( 1547): onCreate
,I/ConfigService( 1547): onDestroy
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 22436(1211KB) AllocSpace objects, 3(48KB) LOS objects, 31% free, 34MB/50MB, paused 2.450ms total 77.874ms
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2729): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2729): Ignoring header User-Agent because its value was null.
,E/LocationReceiver( 1520): Received bad location: null
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024),
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2729): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2729): Ignoring header User-Agent because its value was null.
,I/art     ( 1547): Explicit concurrent mark sweep GC freed 53726(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.002ms total 146.876ms
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 2729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2729): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2729): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
E/PlayEventLogger( 2729): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2729): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2729): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2729): Ignoring header User-Agent because its value was null.
,I/art     (  821): Explicit concurrent mark sweep GC freed 55248(2MB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 35MB/51MB, paused 1.236ms total 91.581ms
,I/ProcessStatsService(  821): Prepared write state in 14ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-12-07-16-12-19.bin
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1547): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1547): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1547): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1547): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1547): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1547): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1547): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1547): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1547): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2729): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2729): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2729): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2729): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2729): Ignoring header User-Agent because its value was null.
,I/ActivityManager(  821): Killing 2441:android.process.acore/u0a5 (adj 11): empty for 1803s
,I/ActivityManager(  821): Killing 2214:com.android.providers.calendar/u0a3 (adj 13): empty for 1819s
,I/ActivityManager(  821): Killing 2891:com.google.android.music:main/u0a66 (adj 13): empty for 1840s
,I/ActivityManager(  821): Killing 2363:com.google.android.calendar/u0a37 (adj 13): empty for 1844s
,I/ActivityManager(  821): Killing 2787:com.google.android.gm/u0a78 (adj 15): empty for 1844s
,I/ActivityManager(  821): Killing 2853:com.google.android.apps.messaging/u0a75 (adj 15): empty for 1846s
,I/art     ( 1547): Explicit concurrent mark sweep GC freed 95018(4MB) AllocSpace objects, 5(551KB) LOS objects, 36% free, 27MB/43MB, paused 1.565ms total 53.624ms
,I/art     ( 1792): Explicit concurrent mark sweep GC freed 14133(1039KB) AllocSpace objects, 6(96KB) LOS objects, 36% free, 27MB/43MB, paused 1.187ms total 32.651ms
,TIME-OUT KILL (timeout was 1800000ms)
```
