#### Test 5065027873d6a28_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2738): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2738): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2738): [1] 5.onFinished: Scheduling replication attempt 2.
,D/AndroidRuntime( 3224): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3224): CheckJNI is OFF
D/AndroidRuntime( 3224): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{34063959 token=Token{28e1f9a0 ActivityRecord{326502a3 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3224): Shutting down VM
I/HotwordDetector( 1490): Closing mic
I/MicrophoneInputStream( 1490): mic_close com.google.android.apps.gsa.speech.audio.u@e3a629c
V/WindowManager(  823): Adding window Window{3740492a u0 Starting com.test.thalitest} at 3 of 8 (after Window{20afb78f u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  823): Start proc 3238:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1490): Hotword detection finished
I/HotwordRecognitionRnr( 1490): Stopping hotword detection.
I/ActivityManager(  823): Killing 2697:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659831571
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  823): Killing 2828:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3238): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3238): Time to load native libraries: 2 ms (timestamps 5774-5776)
I/LibraryLoader( 3238): Expected native library version number "",actual native library version number ""
I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
V/WebViewChromiumFactoryProvider( 3238): Binding Chromium to main looper Looper (main, tid 1) {263bd8af}
I/LibraryLoader( 3238): Expected native library version number "",actual native library version number ""
I/chromium( 3238): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3238): Initializing chromium process, singleProcess=true
W/art     ( 3238): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3238): ApplicationContext is null in ApplicationStatus
E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
W/chromium( 3238): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3238): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3238): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3238): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3238): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9550da:true
D/BluetoothAdapter( 3238): 703426728: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3238): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3238): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3238): CordovaWebView is running on device made by: motorola
W/art     ( 3238): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3238): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3238): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3238): Validating map...
V/WindowManager(  823): Adding window Window{34d3a48a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{3740492a u0 Starting com.test.thalitest})
W/chromium( 3238): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3238): Initialized EGL, version 1.4
D/OpenGLRenderer( 3238): Enabling debug mode 0
I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +705ms (total +1m43s651ms)
I/Keyboard.Facilitator( 1231): onFinishInput()
W/BindingManager( 3238): Cannot call determinedVisibility() - never saw a connection for the pid: 3238
D/JsMessageQueue( 3238): Set native->JS mode to OnlineEventsBridgeMode
I/art     (  823): Explicit concurrent mark sweep GC freed 14994(704KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.326ms total 69.295ms
,D/jxcore_app_log( 3238): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580388992
,D/JX-Cordova( 3238): jxcore cordova android initializing
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
I/kickstart(  873): STATUS: 950272 bytes transferred in 1.000765 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed,
,W/jxcore-log( 3238): Initializing JXcore engine
W/jxcore-log( 3238): JXcore engine is ready
,W/jxcore-log( 3238): Starting JXcore engine
,W/.test.thalitest( 3238): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9665]" dev="sockfs" ino=9665 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3238): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3238): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12878]" dev="sockfs" ino=12878 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3238): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19303]" dev="sockfs" ino=19303 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3238): Platform android
W/jxcore-log( 3238): 
W/jxcore-log( 3238): Process ARCH arm
W/jxcore-log( 3238): 
,I/jxcore-log( 3238): JXcore Cordova bridge is ready!
I/jxcore-log( 3238): 
W/jxcore-log( 3238): JXcore engine is started
,I/chromium( 3238): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3238): Error!: missing ) after argument list
E/jxcore  ( 3238): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3238): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (134 us)
,W/PluginManager( 3238): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,W/IInputConnectionWrapper( 3238): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1231): onFinishInput()
,W/LocationOracleImpl( 1490): Best location was null
,W/ErrorReporter( 1490): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1490): Starting hotword detection.
I/MicrophoneInputStream( 1490): mic_starting com.google.android.apps.gsa.speech.audio.u@2aca21a1
,I/AudioFlinger(  359): AudioFlinger's thread 0xb406f000 ready to run
,W/GCoreFlp( 1750): No location to return for getLastLocation()
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1490): mic_started com.google.android.apps.gsa.speech.audio.u@2aca21a1
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1750): No location to return for getLastLocation()
,I/HotwordWorker( 1490): onReady
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659831571
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/OpenGLRenderer( 1325): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourceType( 1065): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1065): Failure retrieving resources for com.test.thalitest: Resource ID #0x0,
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2738): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2738): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2738): [1] 5.onFinished: Scheduling replication attempt 3.
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 279ms
,I/DreamManagerService(  823): Entering dreamland.
I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,E/wifi    (  823): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  823): cancelDelayedScan -> 1
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/wifi    (  823): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  823): cancelDelayedScan -> 2
I/Keyboard.Facilitator( 1231): onFinishInput(),
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,I/art     ( 1537): Explicit concurrent mark sweep GC freed 21611(1079KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.860ms total 38.458ms
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2738): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2738): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2738): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2738): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2738): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2738): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2738): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2738): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2738): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1231): run()
I/Keyboard.Facilitator( 1231): flushDynamicLanguageModels()
,I/ConfigService( 1537): onCreate,
,I/ConfigService( 1537): onDestroy
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 23874(1207KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.603ms total 89.346ms
,W/GLSActivity( 1537): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2738): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2738): Ignoring header User-Agent because its value was null.
,E/LocationReceiver( 1490): Received bad location: null
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1537): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2738): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2738): 	,at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2738): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2738): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1537): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2738): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2738): Ignoring header User-Agent because its value was null.
,I/art     ( 1537): Explicit concurrent mark sweep GC freed 67612(3MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 1.320ms total 47.452ms
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1537): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2738): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2738): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1537): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2738): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2738): Ignoring header User-Agent because its value was null.
,I/art     (  823): Explicit concurrent mark sweep GC freed 56393(2MB) AllocSpace objects, 5(80KB) LOS objects, 31% free, 35MB/51MB, paused 1.406ms total 90.460ms
,I/ProcessStatsService(  823): Prepared write state in 8ms
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  823): Pruning old procstats: /data/system/procstats/state-2015-12-08-07-15-13.bin
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1537): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1537): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1537): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1537): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1537): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2738): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2738): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2738): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2738): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2738): Ignoring header User-Agent because its value was null.
,I/ActivityManager(  823): Killing 2861:com.google.android.apps.messaging/u0a75 (adj 15): empty for 1801s
,I/ActivityManager(  823): Killing 2796:com.google.android.gm/u0a78 (adj 15): empty for 1800s
,I/ActivityManager(  823): Killing 2357:com.google.android.calendar/u0a37 (adj 15): empty for 1800s
,I/EventLogService( 1780): Opted in for usage reporting
I/EventLogService( 1780): Aggregate from 1449626427071 (log), 1449626427071 (data)
,I/art     ( 1780): Explicit concurrent mark sweep GC freed 15276(1081KB) AllocSpace objects, 4(64KB) LOS objects, 36% free, 27MB/43MB, paused 1.416ms total 92.903ms
,I/GLSUser ( 1537): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1537): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1537): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1537): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1537): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1780): Unknown tag: snet_gcore
W/EventLogAggregator( 1780): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1780): dumping service [account]
,I/ActivityManager(  823): Killing 2434:android.process.acore/u0a5 (adj 13): empty for 1821s
,I/ActivityManager(  823): Killing 2205:com.android.providers.calendar/u0a3 (adj 13): empty for 1834s
,I/ActivityManager(  823): Killing 2900:com.google.android.music:main/u0a66 (adj 15): empty for 1855s
,TIME-OUT KILL (timeout was 1800000ms)
```
