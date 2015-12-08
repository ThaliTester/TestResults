#### Test 50650278cc6513d_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 25178(1337KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.282ms total 56.192ms
I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2724): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2724): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3192): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3192): CheckJNI is OFF
D/AndroidRuntime( 3192): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{9fe7402 token=Token{33cb414d ActivityRecord{73f18e4 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  819): Adding window Window{b2ecb6f u0 Starting com.test.thalitest} at 3 of 8 (after Window{2bf2ce46 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1524): Closing mic
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@2fd27023
D/AndroidRuntime( 3192): Shutting down VM
I/ActivityManager(  819): Start proc 3207:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/HotwordRecognitionRnr( 1524): Hotword detection finished
W/GCoreFlp( 1751): No location to return for getLastLocation()
I/ActivityManager(  819): Killing 2683:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659745555
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  819): Killing 2817:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  869): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  869): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  869): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3207): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3207): Time to load native libraries: 4 ms (timestamps 4671-4675)
I/LibraryLoader( 3207): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3207): Binding Chromium to main looper Looper (main, tid 1) {22e7a17d}
,I/LibraryLoader( 3207): Expected native library version number "",actual native library version number ""
I/chromium( 3207): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3207): Initializing chromium process, singleProcess=true
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3207): ApplicationContext is null in ApplicationStatus
,W/chromium( 3207): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3207): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3207): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3207): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3207): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e8f6e5f:true
,D/BluetoothAdapter( 3207): 316946878: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3207): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3207): CordovaWebView is running on device made by: motorola
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3207): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3207): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3207): Validating map...
,I/art     (  819): Explicit concurrent mark sweep GC freed 19728(952KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.722ms total 66.535ms
,V/WindowManager(  819): Adding window Window{196ad4f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{b2ecb6f u0 Starting com.test.thalitest})
,W/chromium( 3207): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3207): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3207): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +976ms (total +2m2s583ms)
,I/Keyboard.Facilitator( 1236): onFinishInput()
,W/BindingManager( 3207): Cannot call determinedVisibility() - never saw a connection for the pid: 3207
,D/JsMessageQueue( 3207): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3207): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576258688
,D/JX-Cordova( 3207): jxcore cordova android initializing
,I/kickstart(  869): STATUS: Received file 'm9kefs2'
I/kickstart(  869): STATUS: 950272 bytes transferred in 0.994264 seconds
,I/kickstart(  869): STATUS: Successfully downloaded files from target 
I/kickstart(  869): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  869): STATUS: Sahara protocol completed
,W/jxcore-log( 3207): Initializing JXcore engine
W/jxcore-log( 3207): JXcore engine is ready
,W/jxcore-log( 3207): Starting JXcore engine
,W/.test.thalitest( 3207): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10432]" dev="sockfs" ino=10432 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3207): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3207): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10616]" dev="sockfs" ino=10616 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3207): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19113]" dev="sockfs" ino=19113 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3207): Platform android
W/jxcore-log( 3207): 
W/jxcore-log( 3207): Process ARCH arm
W/jxcore-log( 3207): 
,I/jxcore-log( 3207): JXcore Cordova bridge is ready!
I/jxcore-log( 3207): 
W/jxcore-log( 3207): JXcore engine is started
,I/Choreographer( 3207): Skipped 135 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3207): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3207): Error!: missing ) after argument list
E/jxcore  ( 3207): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3207): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
,W/PluginManager( 3207): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 62ms. Plugin should use CordovaInterface.getThreadPool().
,W/IInputConnectionWrapper( 3207): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1236): onFinishInput()
,W/LocationOracleImpl( 1524): Best location was null
,W/ErrorReporter( 1524): reportError [type: 29, code: 917507]: null
,I/HotwordRecognitionRnr( 1524): Starting hotword detection.
,W/GCoreFlp( 1751): No location to return for getLastLocation()
,I/MicrophoneInputStream( 1524): mic_starting com.google.android.apps.gsa.speech.audio.u@120b5a88
,I/AudioFlinger(  357): AudioFlinger's thread 0xb406a000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1524): mic_started com.google.android.apps.gsa.speech.audio.u@120b5a88
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,W/GCoreFlp( 1751): No location to return for getLastLocation()
,I/HotwordWorker( 1524): onReady
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659745555
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/OpenGLRenderer( 1315): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourceType( 1070): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1070): Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  819): Display changed displayId=0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  819): Excessive delay in setPowerMode(): 282ms
,I/DreamManagerService(  819): Entering dreamland.
I/PowerManagerService(  819): Dozing...
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,E/wifi    (  819): android_net_wifi_getLinkLayerStats: failed to get link statistics
D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
E/WifiStateMachine(  819): cancelDelayedScan -> 1
,E/wifi    (  819): android_net_wifi_getLinkLayerStats: failed to get link statistics
I/Keyboard.Facilitator( 1236): onFinishInput()
,E/WifiStateMachine(  819): cancelDelayedScan -> 2
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2724): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2724): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2724): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 2724): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2724): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2724): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2724): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1236): run()
I/Keyboard.Facilitator( 1236): flushDynamicLanguageModels()
,I/ConfigService( 1498): onCreate
,I/ConfigService( 1498): onDestroy
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2724): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2724): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2724): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2724): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2724): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2724): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2724): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2724): Ignoring header User-Agent because its value was null.
,I/art     (  819): Explicit concurrent mark sweep GC freed 24647(1245KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 1.232ms total 68.258ms

```
