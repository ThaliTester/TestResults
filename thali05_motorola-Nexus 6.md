#### Test 50650278352fc1f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 4.
D/AndroidRuntime( 3177): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3177): CheckJNI is OFF
D/AndroidRuntime( 3177): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{31d5b87f token=Token{3bed059e ActivityRecord{2850e7d9 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3177): Shutting down VM
I/MicrophoneInputStream( 1545): mic_close com.google.android.apps.gsa.speech.audio.u@2eb819a
I/HotwordDetector( 1545): Closing mic
V/WindowManager(  822): Adding window Window{265a4538 u0 Starting com.test.thalitest} at 3 of 8 (after Window{5e04e6c u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  822): Start proc 3192:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1545): Stopping hotword detection.
I/HotwordRecognitionRnr( 1545): Hotword detection finished
W/GCoreFlp( 1759): No location to return for getLastLocation()
I/ActivityManager(  822): Killing 2673:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659860243
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  822): Killing 2807:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3192): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3192): Time to load native libraries: 5 ms (timestamps 8498-8503)
I/LibraryLoader( 3192): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3192): Binding Chromium to main looper Looper (main, tid 1) {2720010c}
,I/LibraryLoader( 3192): Expected native library version number "",actual native library version number ""
I/chromium( 3192): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3192): Initializing chromium process, singleProcess=true,
W/art     ( 3192): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3192): ApplicationContext is null in ApplicationStatus
,W/chromium( 3192): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 3192): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 3192): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3192): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3192): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,I/art     (  822): Explicit concurrent mark sweep GC freed 19688(899KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.677ms total 85.932ms
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31dc6105:true
,D/BluetoothAdapter( 3192): 1045570040: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3192): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3192): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3192): CordovaWebView is running on device made by: motorola
,W/art     ( 3192): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3192): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3192): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3192): Validating map...
,V/WindowManager(  822): Adding window Window{1d20bf98 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{265a4538 u0 Starting com.test.thalitest})
,W/chromium( 3192): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3192): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3192): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +1s53ms (total +2m6s85ms)
,I/Keyboard.Facilitator( 1219): onFinishInput()
,W/BindingManager( 3192): Cannot call determinedVisibility() - never saw a connection for the pid: 3192
,D/JsMessageQueue( 3192): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3192): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576270080
D/JX-Cordova( 3192): jxcore cordova android initializing
,I/kickstart(  869): STATUS: Received file 'm9kefs2'
I/kickstart(  869): STATUS: 950272 bytes transferred in 0.987070 seconds
I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,W/jxcore-log( 3192): Initializing JXcore engine
W/jxcore-log( 3192): JXcore engine is ready
,W/jxcore-log( 3192): Starting JXcore engine,
,W/.test.thalitest( 3192): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13033]" dev="sockfs" ino=13033 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3192): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/.test.thalitest( 3192): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9841]" dev="sockfs" ino=9841 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3192): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20802]" dev="sockfs" ino=20802 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3192): Platform android
,W/jxcore-log( 3192): 
W/jxcore-log( 3192): Process ARCH arm
W/jxcore-log( 3192): 
,I/jxcore-log( 3192): JXcore Cordova bridge is ready!
I/jxcore-log( 3192): 
W/jxcore-log( 3192): JXcore engine is started
,I/Choreographer( 3192): Skipped 132 frames!  The application may be doing too much work on its main thread.
I/chromium( 3192): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3192): Error!: missing ) after argument list
E/jxcore  ( 3192): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3192): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (284 us)
,W/PluginManager( 3192): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator( 1219): onFinishInput()
,W/IInputConnectionWrapper( 3192): showStatusIcon on inactive InputConnection
,W/LocationOracleImpl( 1545): Best location was null
,W/ErrorReporter( 1545): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1545): Starting hotword detection.
,I/MicrophoneInputStream( 1545): mic_starting com.google.android.apps.gsa.speech.audio.u@3abefc3b
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4064000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1545): mic_started com.google.android.apps.gsa.speech.audio.u@3abefc3b
,I/art     ( 1545): Background sticky concurrent mark sweep GC freed 76538(8MB) AllocSpace objects, 8(753KB) LOS objects, 22% free, 27MB/35MB, paused 1.890ms total 111.248ms
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1759): No location to return for getLastLocation()
,I/HotwordWorker( 1545): onReady
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659860243
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/OpenGLRenderer( 1303): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourceType( 1071): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1071): Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  278): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0,
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  278): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 271ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,E/wifi    (  822): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  822): cancelDelayedScan -> 1
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,I/Keyboard.Facilitator( 1219): onFinishInput()
,E/wifi    (  822): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  822): cancelDelayedScan -> 2
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1219): run()
,I/Keyboard.Facilitator( 1219): flushDynamicLanguageModels()
,I/ConfigService( 1517): onCreate
,I/ConfigService( 1517): onDestroy
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1517): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1517): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1517): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2715): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2715): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2715): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2715): Ignoring header User-Agent because its value was null.
,I/art     (  822): Explicit concurrent mark sweep GC freed 23396(1186KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.923ms total 83.489ms
,E/LocationReceiver( 1545): Received bad location: null
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1517): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1517): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1517): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2715): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2715): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2715): 	,at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2715): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2715): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2715): Ignoring header User-Agent because its value was null.
,D/Finsky  ( 2715): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1517): Explicit concurrent mark sweep GC freed 52740(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.175ms total 45.320ms
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2715): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2715): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2715): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 2715): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 2715): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2715): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1759): client connected with version: 7571000
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 1.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 4.
,I/art     (  822): Explicit concurrent mark sweep GC freed 31497(1486KB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.360ms total 69.776ms
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2715): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2715): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2715): [1] 5.onFinished: Giving up after 6 failures.
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1517): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1517): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1517): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2715): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2715): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2715): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2715): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1517): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1517): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1517): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2715): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2715): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2715): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2715): Ignoring header User-Agent because its value was null.
,I/art     ( 1517): Explicit concurrent mark sweep GC freed 69746(3MB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 2.386ms total 83.748ms
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1517): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1517): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1517): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2715): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2715): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2715): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2715): Ignoring header User-Agent because its value was null.
,I/ProcessStatsService(  822): Prepared write state in 17ms
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1517): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1517): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1517): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1517): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1517): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2715): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2715): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2715): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2715): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2715): Ignoring header User-Agent because its value was null.
,I/ProcessStatsService(  822): Pruning old procstats: /data/system/procstats/state-2015-12-07-15-36-31.bin
,I/ActivityManager(  822): Killing 2839:com.google.android.apps.messaging/u0a75 (adj 15): empty for 1801s
,I/ActivityManager(  822): Killing 2360:com.google.android.calendar/u0a37 (adj 13): empty for 1800s
,I/ActivityManager(  822): Killing 2773:com.google.android.gm/u0a78 (adj 13): empty for 1800s
,I/EventLogService( 1787): Opted in for usage reporting
I/EventLogService( 1787): Aggregate from 1449587749008 (log), 1449587749008 (data)
,I/art     ( 1787): Explicit concurrent mark sweep GC freed 15115(1064KB) AllocSpace objects, 4(64KB) LOS objects, 36% free, 27MB/43MB, paused 1.841ms total 53.825ms
,I/GLSUser ( 1517): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1517): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1517): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1517): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1517): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1787): Unknown tag: snet_gcore
W/EventLogAggregator( 1787): Unknown tag: snet_launch_service
,I/art     (  822): Explicit concurrent mark sweep GC freed 49755(2MB) AllocSpace objects, 9(302KB) LOS objects, 31% free, 35MB/51MB, paused 1.392ms total 71.275ms
,I/ServiceDumpSys( 1787): dumping service [account]
,I/ActivityManager(  822): Killing 1385:android.process.acore/u0a5 (adj 13): empty for 1818s
,I/ActivityManager(  822): Killing 2211:com.android.providers.calendar/u0a3 (adj 13): empty for 1834s
,I/ActivityManager(  822): Killing 2876:com.google.android.music:main/u0a66 (adj 15): empty for 1855s
,TIME-OUT KILL (timeout was 1800000ms)
```
