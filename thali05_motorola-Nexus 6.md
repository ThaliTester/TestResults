#### Test 50650278eab32a5_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2720): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2720): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2720): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3205): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3205): CheckJNI is OFF
D/AndroidRuntime( 3205): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{191e5d41 token=Token{17061c28 ActivityRecord{36a17a4b u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3205): Shutting down VM
V/WindowManager(  822): Adding window Window{25021772 u0 Starting com.test.thalitest} at 3 of 8 (after Window{2a34fc1d u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1526): mic_close com.google.android.apps.gsa.speech.audio.u@81c4574
I/HotwordDetector( 1526): Closing mic
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/ActivityManager(  822): Start proc 3219:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1526): Stopping hotword detection.
I/HotwordRecognitionRnr( 1526): Hotword detection finished
I/ActivityManager(  822): Killing 2679:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/ActivityManager(  822): Killing 2813:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3219): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701901587
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 3219): Time to load native libraries: 7 ms (timestamps 5513-5520)
I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3219): Binding Chromium to main looper Looper (main, tid 1) {2238d63d},
,I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
I/chromium( 3219): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3219): Initializing chromium process, singleProcess=true
,W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring,
E/SysUtils( 3219): ApplicationContext is null in ApplicationStatus
,W/chromium( 3219): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,W/chromium( 3219): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3219): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82b4122:true
,D/BluetoothAdapter( 3219): 752077694: getState() :  mService = null. Returning STATE_OFF
,I/art     (  822): Explicit concurrent mark sweep GC freed 20089(965KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.656ms total 96.418ms
,I/art     ( 1495): Explicit concurrent mark sweep GC freed 26059(1389KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.134ms total 32.548ms
,W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3219): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3219): CordovaWebView is running on device made by: motorola
,W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3219): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3219): Validating map...
,V/WindowManager(  822): Adding window Window{108a36d2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{25021772 u0 Starting com.test.thalitest})
,W/chromium( 3219): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3219): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3219): Enabling debug mode 0
,I/Keyboard.Facilitator( 1212): onFinishInput()
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +1s35ms (total +2m1s917ms)
,W/BindingManager( 3219): Cannot call determinedVisibility() - never saw a connection for the pid: 3219
,D/JsMessageQueue( 3219): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3219): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580384896
D/JX-Cordova( 3219): jxcore cordova android initializing
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.988238 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed,
,W/jxcore-log( 3219): Initializing JXcore engine
W/jxcore-log( 3219): JXcore engine is ready
,W/jxcore-log( 3219): Starting JXcore engine,
,W/.test.thalitest( 3219): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11511]" dev="sockfs" ino=11511 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/.test.thalitest( 3219): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3219): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11217]" dev="sockfs" ino=11217 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/.test.thalitest( 3219): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20089]" dev="sockfs" ino=20089 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3219): Platform android
W/jxcore-log( 3219): 
W/jxcore-log( 3219): Process ARCH arm
W/jxcore-log( 3219): 
,I/jxcore-log( 3219): JXcore Cordova bridge is ready!
I/jxcore-log( 3219): 
W/jxcore-log( 3219): JXcore engine is started
,I/Choreographer( 3219): Skipped 128 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 3219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3219): Error!: missing ) after argument list
,E/jxcore  ( 3219): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3219): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1420 us)
,W/PluginManager( 3219): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 67ms. Plugin should use CordovaInterface.getThreadPool().
,W/IInputConnectionWrapper( 3219): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/LocationOracleImpl( 1526): Best location was null
,W/ErrorReporter( 1526): reportError [type: 29, code: 917507]: null
,W/GCoreFlp( 1753): No location to return for getLastLocation()
,I/HotwordRecognitionRnr( 1526): Starting hotword detection.
,I/MicrophoneInputStream( 1526): mic_starting com.google.android.apps.gsa.speech.audio.u@361c9524
,I/AudioFlinger(  357): AudioFlinger's thread 0xb2003000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1526): mic_started com.google.android.apps.gsa.speech.audio.u@361c9524
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1753): No location to return for getLastLocation()
,I/HotwordWorker( 1526): onReady
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701901587
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/BindingManager( 3219): Cannot call determinedVisibility() - never saw a connection for the pid: 3219
,W/OpenGLRenderer( 1310): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourceType( 1064): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1064): Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  822): Display changed displayId=0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 267ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/wifi    (  822): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  822): cancelDelayedScan -> 1
,I/Keyboard.Facilitator( 1212): onFinishInput()
,E/wifi    (  822): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  822): cancelDelayedScan -> 2
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2720): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2720): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2720): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2720): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2720): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2720): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2720): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2720): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2720): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1212): run()
I/Keyboard.Facilitator( 1212): flushDynamicLanguageModels()
,I/ConfigService( 1495): onCreate
,I/ConfigService( 1495): onDestroy
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 22734(1149KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.625ms total 52.083ms
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1495): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1495): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1495): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2720): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
E/PlayEventLogger( 2720): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2720): Ignoring header User-Agent because its value was null.
,E/LocationReceiver( 1526): Received bad location: null
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1495): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1495): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1495): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 2720): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2720): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2720): Ignoring header User-Agent because its value was null.
,I/art     ( 1495): Explicit concurrent mark sweep GC freed 55017(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.812ms total 124.253ms
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1495): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1495): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1495): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2720): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2720): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1495): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1495): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1495): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2720): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 2720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
E/PlayEventLogger( 2720): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2720): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1495): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1495): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113),
W/GLSActivity( 1495): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2720): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2720): Ignoring header User-Agent because its value was null.
,I/art     (  822): Explicit concurrent mark sweep GC freed 53895(2MB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 35MB/51MB, paused 3.001ms total 84.533ms
,I/art     ( 1785): Explicit concurrent mark sweep GC freed 14513(1025KB) AllocSpace objects, 4(64KB) LOS objects, 36% free, 27MB/43MB, paused 1.587ms total 41.675ms
,I/ProcessStatsService(  822): Prepared write state in 20ms
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1495): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1495): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1495): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1495): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1495): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  822): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-26.bin
,W/GLSActivity( 1495): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1495): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1495): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1495): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1495): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2720): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2720): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2720): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2720): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2720): Ignoring header User-Agent because its value was null.
,I/ActivityManager(  822): Killing 2882:com.google.android.music:main/u0a66 (adj 13): empty for 1811s
,I/ActivityManager(  822): Killing 2352:com.google.android.calendar/u0a37 (adj 13): empty for 1814s
,I/ActivityManager(  822): Killing 2778:com.google.android.gm/u0a78 (adj 13): empty for 1815s
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 2778
I/ActivityManager(  822): Killing 2845:com.google.android.apps.messaging/u0a75 (adj 15): empty for 1817s
,I/ActivityManager(  822): Killing 1388:android.process.acore/u0a5 (adj 15): empty for 1836s
,I/ActivityManager(  822): Killing 2927:com.android.providers.calendar/u0a3 (adj 15): empty for 1850s
,I/art     ( 1495): Explicit concurrent mark sweep GC freed 93257(4MB) AllocSpace objects, 5(551KB) LOS objects, 36% free, 27MB/43MB, paused 2.327ms total 60.712ms
,TIME-OUT KILL (timeout was 1800000ms)
```
