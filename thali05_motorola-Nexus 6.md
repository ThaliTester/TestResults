#### Test 5065027865f659b_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2718): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2718): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2718): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3179): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3179): CheckJNI is OFF
D/AndroidRuntime( 3179): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{231df4e token=Token{57f5a49 ActivityRecord{2c584850 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3179): Shutting down VM
V/WindowManager(  822): Adding window Window{2468bc8b u0 Starting com.test.thalitest} at 3 of 8 (after Window{3df08285 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1520): Closing mic
I/MicrophoneInputStream( 1520): mic_close com.google.android.apps.gsa.speech.audio.u@80af55a
I/ActivityManager(  822): Start proc 3193:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1520): Hotword detection finished
I/HotwordRecognitionRnr( 1520): Stopping hotword detection.
I/ActivityManager(  822): Killing 2677:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659438355
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  822): Killing 2811:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3193): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3193): Time to load native libraries: 4 ms (timestamps 3732-3736)
I/LibraryLoader( 3193): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3193): Binding Chromium to main looper Looper (main, tid 1) {3b341f6e}
,I/LibraryLoader( 3193): Expected native library version number "",actual native library version number "",
I/chromium( 3193): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3193): Initializing chromium process, singleProcess=true,
W/art     ( 3193): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3193): ApplicationContext is null in ApplicationStatus
,W/chromium( 3193): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3193): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3193): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3193): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3193): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1765de7b:true
,D/BluetoothAdapter( 3193): 554091642: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 24377(1286KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.368ms total 43.280ms
,W/art     ( 3193): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3193): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3193): CordovaWebView is running on device made by: motorola
,W/art     ( 3193): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3193): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3193): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3193): Validating map...
,V/WindowManager(  822): Adding window Window{5a75c6b u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{2468bc8b u0 Starting com.test.thalitest})
,W/chromium( 3193): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  822): Explicit concurrent mark sweep GC freed 17216(831KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.475ms total 81.612ms
,I/OpenGLRenderer( 3193): Initialized EGL, version 1.4
D/OpenGLRenderer( 3193): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +1s1ms (total +1m51s667ms)
,I/Keyboard.Facilitator( 1232): onFinishInput()
,W/BindingManager( 3193): Cannot call determinedVisibility() - never saw a connection for the pid: 3193
,D/JsMessageQueue( 3193): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 0.994651 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3193): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576182400
D/JX-Cordova( 3193): jxcore cordova android initializing
,W/jxcore-log( 3193): Initializing JXcore engine
W/jxcore-log( 3193): JXcore engine is ready
,W/jxcore-log( 3193): Starting JXcore engine
,W/.test.thalitest( 3193): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11530]" dev="sockfs" ino=11530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3193): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3193): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11716]" dev="sockfs" ino=11716 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3193): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21581]" dev="sockfs" ino=21581 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3193): Platform android
W/jxcore-log( 3193): 
W/jxcore-log( 3193): Process ARCH arm
W/jxcore-log( 3193): 
,I/jxcore-log( 3193): JXcore Cordova bridge is ready!
I/jxcore-log( 3193): 
W/jxcore-log( 3193): JXcore engine is started
I/Choreographer( 3193): Skipped 135 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3193): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3193): Error!: missing ) after argument list
E/jxcore  ( 3193): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (220 us)
,W/PluginManager( 3193): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,I/chromium( 3193): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/Keyboard.Facilitator( 1232): onFinishInput()
,W/IInputConnectionWrapper( 3193): showStatusIcon on inactive InputConnection
,W/LocationOracleImpl( 1520): Best location was null
,W/ErrorReporter( 1520): reportError [type: 29, code: 917507]: null
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,I/HotwordRecognitionRnr( 1520): Starting hotword detection.
,I/MicrophoneInputStream( 1520): mic_starting com.google.android.apps.gsa.speech.audio.u@13f5acd0
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/AudioFlinger(  359): AudioFlinger's thread 0xb40ed000 ready to run
,I/MicrophoneInputStream( 1520): mic_started com.google.android.apps.gsa.speech.audio.u@13f5acd0
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,I/HotwordWorker( 1520): onReady
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659438355
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/OpenGLRenderer( 1308): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourceType( 1065): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1065): Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 280ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,E/wifi    (  822): android_net_wifi_getLinkLayerStats: failed to get link statistics
D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
E/WifiStateMachine(  822): cancelDelayedScan -> 1
,I/Keyboard.Facilitator( 1232): onFinishInput()
E/wifi    (  822): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  822): cancelDelayedScan -> 2
D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2718): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2718): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2718): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2718): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2718): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2718): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2718): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2718): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2718): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1232): run()
I/Keyboard.Facilitator( 1232): flushDynamicLanguageModels()
,I/ConfigService( 1483): onCreate
,I/ConfigService( 1483): onDestroy
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2718): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2718): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2718): ,	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2718): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2718): ,	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2718): Ignoring header User-Agent because its value was null.
,I/art     (  822): Explicit concurrent mark sweep GC freed 24739(1241KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.650ms total 69.084ms
,E/LocationReceiver( 1520): Received bad location: null
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2718): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2718): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2718): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2718): Ignoring header User-Agent because its value was null.
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 55351(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.225ms total 44.963ms
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2718): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2718): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867),
E/PlayEventLogger( 2718): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2718): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2718): Ignoring header User-Agent because its value was null.
,I/EventLogService( 1781): Opted in for usage reporting
I/EventLogService( 1781): Aggregate from 1449597569585 (log), 1449597569585 (data)
,W/EventLogAggregator( 1781): Unknown tag: snet_gcore
W/EventLogAggregator( 1781): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1781): dumping service [account]
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2718): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2718): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2718): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2718): Ignoring header User-Agent because its value was null.
,I/art     ( 1781): Explicit concurrent mark sweep GC freed 15712(1119KB) AllocSpace objects, 6(96KB) LOS objects, 36% free, 27MB/43MB, paused 2.209ms total 76.517ms
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2718): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2718): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2718): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2718): Ignoring header User-Agent because its value was null.
,I/art     (  822): Explicit concurrent mark sweep GC freed 54646(2MB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 35MB/51MB, paused 3.242ms total 89.563ms
,I/ProcessStatsService(  822): Prepared write state in 18ms
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2718): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2718): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2718): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2718): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2718): Ignoring header User-Agent because its value was null.
,I/ProcessStatsService(  822): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-13-06.bin
,I/ActivityManager(  822): Killing 2843:com.google.android.apps.messaging/u0a75 (adj 15): empty for 1801s,
,I/ActivityManager(  822): Killing 2777:com.google.android.gm/u0a78 (adj 15): empty for 1800s
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 86558(3MB) AllocSpace objects, 5(551KB) LOS objects, 36% free, 27MB/43MB, paused 1.351ms total 47.253ms
,I/ActivityManager(  822): Killing 2350:com.google.android.calendar/u0a37 (adj 15): empty for 1800s
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Killing 2430:android.process.acore/u0a5 (adj 13): empty for 1822s
,I/ActivityManager(  822): Killing 2203:com.android.providers.calendar/u0a3 (adj 13): empty for 1833s
,I/ActivityManager(  822): Killing 2878:com.google.android.music:main/u0a66 (adj 15): empty for 1855s
,TIME-OUT KILL (timeout was 1800000ms)
```
