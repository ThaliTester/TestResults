#### Test 52383621d5a0cb8_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=2.68 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,D/AndroidRuntime( 3664): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3664): CheckJNI is OFF
D/AndroidRuntime( 3664): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{1517b8e1 token=Token{1e232248 ActivityRecord{16d444eb u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3664): Shutting down VM
V/WindowManager(  819): Adding window Window{10d1ec92 u0 Starting com.test.thalitest} at 3 of 8 (after Window{1798127 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1521): mic_close com.google.android.apps.gsa.speech.audio.u@1ff616b7
I/HotwordDetector( 1521): Closing mic
I/ActivityManager(  819): Start proc 3679:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1521): Stopping hotword detection.
I/HotwordRecognitionRnr( 1521): Hotword detection finished
I/art     (  367): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 306us total 23.633ms
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 303us total 15.518ms
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 290us total 13.787ms
I/ActivityManager(  819): Killing 3110:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  819): Killing 2720:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/WebViewFactory( 3679): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659430163
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 3679): Time to load native libraries: 2 ms (timestamps 3054-3056)
I/LibraryLoader( 3679): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3679): Binding Chromium to main looper Looper (main, tid 1) {2f8c26ae}
,I/LibraryLoader( 3679): Expected native library version number "",actual native library version number ""
I/chromium( 3679): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3679): Initializing chromium process, singleProcess=true,
W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3679): ApplicationContext is null in ApplicationStatus
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,W/chromium( 3679): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3679): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3679): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24aa9e42:true
,W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3679): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3679): CordovaWebView is running on device made by: motorola
,W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3679): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3679): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3679): Validating map...
,V/WindowManager(  819): Adding window Window{cab1bf2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{10d1ec92 u0 Starting com.test.thalitest})
,W/chromium( 3679): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3679): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3679): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +1s95ms (total +1m50s542ms)
,I/Keyboard.Facilitator( 1273): onFinishInput()
,W/BindingManager( 3679): Cannot call determinedVisibility() - never saw a connection for the pid: 3679
,D/JsMessageQueue( 3679): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3679): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1574279680
D/JX-Cordova( 3679): jxcore cordova android initializing
,I/kickstart(  870): STATUS: Received file 'm9kefs1'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.991391 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed,
,W/jxcore-log( 3679): Initializing JXcore engine
W/jxcore-log( 3679): JXcore engine is ready
,W/jxcore-log( 3679): Starting JXcore engine,
,W/.test.thalitest( 3679): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10717]" dev="sockfs" ino=10717 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3679): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/.test.thalitest( 3679): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9815]" dev="sockfs" ino=9815 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3679): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23722]" dev="sockfs" ino=23722 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3679): Platform android
W/jxcore-log( 3679): 
W/jxcore-log( 3679): Process ARCH arm
W/jxcore-log( 3679): 
,I/jxcore-log( 3679): JXcore Cordova bridge is ready!
I/jxcore-log( 3679): 
W/jxcore-log( 3679): JXcore engine is started
I/Choreographer( 3679): Skipped 146 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3679): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3679): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 3679): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 3679): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (176 us)
,W/PluginManager( 3679): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
,I/Keyboard.Facilitator( 1273): onFinishInput()
,W/IInputConnectionWrapper( 3679): showStatusIcon on inactive InputConnection
,W/LocationOracleImpl( 1521): Best location was null
,I/HotwordRecognitionRnr( 1521): Starting hotword detection.
,I/MicrophoneInputStream( 1521): mic_starting com.google.android.apps.gsa.speech.audio.u@28c2eed0
,I/AudioFlinger(  356): AudioFlinger's thread 0xb40e8000 ready to run
,I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1521): mic_started com.google.android.apps.gsa.speech.audio.u@28c2eed0
,D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
,I/art     ( 1844): Explicit concurrent mark sweep GC freed 15461(963KB) AllocSpace objects, 9(144KB) LOS objects, 37% free, 26MB/42MB, paused 833us total 55.149ms
,E/DataBuffer( 1844): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e34aa7)
,I/HotwordWorker( 1521): onReady
,I/art     (  819): Explicit concurrent mark sweep GC freed 31897(1565KB) AllocSpace objects, 11(270KB) LOS objects, 31% free, 35MB/51MB, paused 1.933ms total 73.001ms
,E/LocationReceiver( 1521): Received bad location: null
,E/LocationReceiver( 1521): Received bad location: null
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659430163
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/OpenGLRenderer( 1387): Incorrectly called buildLayer on View: ew, destroying layer...
,W/ResourceType( 1064): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1064): Failure retrieving resources for com.test.thalitest: Resource ID #0x0
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3052): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3052): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.05 rxSuccessRate=2.51 targetRoamBSSID=any RSSI=-47
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb6082000
I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/qdhwcomposer(  278): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  819): Display changed displayId=0
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  278): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 269ms
,I/DreamManagerService(  819): Entering dreamland.
,I/PowerManagerService(  819): Dozing...
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 11
,E/native  (  819): do suspend false
,I/Keyboard.Facilitator( 1273): onFinishInput()
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): cancelDelayedScan -> 13
,E/native  (  819): do suspend true
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3618): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169524, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82),
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at blb.a(PG:3937)
E/HttpOperation( 3387): 	at czp.a(PG:18188)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125)
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 12 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 14 more
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82)
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at hec.a(PG:42)
E/HttpOperation( 3387): 	at hee.a(PG:102)
E/HttpOperation( 3387): 	at czr.a(PG:65)
E/HttpOperation( 3387): 	at kka.a(PG:108)
,E/HttpOperation( 3387): 	at czp.a(PG:19176)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125),
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 15 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 17 more
,E/ExperimentLoader( 3387): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): 	at jdm.a(PG:82)
E/ExperimentLoader( 3387): 	at jcs.o(PG:406)
E/ExperimentLoader( 3387): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3387): 	at jcs.i(PG:143)
E/ExperimentLoader( 3387): 	at hec.a(PG:42)
E/ExperimentLoader( 3387): 	at hee.a(PG:102)
E/ExperimentLoader( 3387): 	at czr.a(PG:65)
E/ExperimentLoader( 3387): 	at kka.a(PG:108)
E/ExperimentLoader( 3387): 	at czp.a(PG:19176)
E/ExperimentLoader( 3387): 	at czp.a(PG:9081)
E/ExperimentLoader( 3387): 	at czq.run(PG:1686)
E/ExperimentLoader( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3387): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3387): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3387): 	at jdm.a(PG:77)
E/ExperimentLoader( 3387): 	... 15 more
E/ExperimentLoader( 3387): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3387): 	at fal.a(PG:38)
E/ExperimentLoader( 3387): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3387): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 169860, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1234): Explicit concurrent mark sweep GC freed 28175(1654KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2.053ms total 60.875ms
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3052): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3052): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  819): Start proc 3771:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/VacuumService( 1234): Vacuum at: now=1449056564419 tag=VacuumService
,V/GoogleAuthProtoRequest( 3771): [401] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3771): [401] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3771): [401] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3771): [402] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GoogleURLConnFactory( 1234): Using platform SSLCertificateSocketFactory
,W/Uploader( 1234): No account for auth token provided
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 38478(1823KB) AllocSpace objects, 8(222KB) LOS objects, 31% free, 35MB/51MB, paused 1.368ms total 82.791ms
,W/ExperimentUpdateService( 3771): [402] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3771): [402] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1234): No account for auth token provided
,W/Uploader( 1234): No account for auth token provided
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1234): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1234): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1234): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1234): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1234): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1234): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1234): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1234): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1234): No account for auth token provided
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1234): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1234): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1234): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1234): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1234): No account for auth token provided
,W/Uploader( 1234): No account for auth token provided
,W/Uploader( 1234): No account for auth token provided
,W/Uploader( 1234): No account for auth token provided
,W/Uploader( 1234): No account for auth token provided
,W/Uploader( 1234):  no longer exists, so no auth token.
,W/Uploader( 1234): No account for auth token provided
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1234): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1234): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1234): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1234): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1234): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1234): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3052): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3052): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/KeepSync( 3588): Connecting to GoogleApiClient
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1819): Handling authorization failure
E/ClientConnectionOperation( 1819): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1819): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1819): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1819): ,	... 7 more
,I/art     ( 1819): Explicit concurrent mark sweep GC freed 37884(2MB) AllocSpace objects, 10(183KB) LOS objects, 35% free, 29MB/45MB, paused 1.615ms total 92.288ms
,V/KeepSync( 3588): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3588): IOException
E/KeepSync( 3588): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3588): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3588): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3588): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3588): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3588): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3588): 	... 10 more
W/KeepSync( 3588): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 171527, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3771): [403] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3771): [403] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3771): [403] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): ,	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110),
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3052): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3052): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1273): run()
I/Keyboard.Facilitator( 1273): flushDynamicLanguageModels()
,I/ConfigService( 1234): onCreate
,I/ConfigService( 1234): onDestroy
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1234): Explicit concurrent mark sweep GC freed 68065(3MB) AllocSpace objects, 6(590KB) LOS objects, 36% free, 27MB/43MB, paused 1.297ms total 53.788ms
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3618): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 292253, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3771): [404] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  819): Explicit concurrent mark sweep GC freed 30924(1337KB) AllocSpace objects, 3(142KB) LOS objects, 30% free, 36MB/52MB, paused 1.341ms total 63.789ms
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3771): [404] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3771): [404] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/ActivityManager(  819): Start proc 3845:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3845): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3845):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3845):   adb logcat -s GAv4
,W/GAv4    ( 3845): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GAv4    ( 3845): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,E/HttpOperation( 3387): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 3387): 	at jdm.a(PG:82),
E/HttpOperation( 3387): ,	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
,E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at blb.a(PG:3937),
E/HttpOperation( 3387): 	at czp.a(PG:18188)
E/HttpOperation( 3387): ,	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686),
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125),
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 12 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 14 more
,W/GAv4    ( 3845): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82)
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at hec.a(PG:42)
E/HttpOperation( 3387): 	at hee.a(PG:102)
E/HttpOperation( 3387): 	at czr.a(PG:65)
E/HttpOperation( 3387): 	at kka.a(PG:108)
E/HttpOperation( 3387): 	at czp.a(PG:19176)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125)
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 15 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 17 more
E/ExperimentLoader( 3387): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): 	at jdm.a(PG:82)
E/ExperimentLoader( 3387): 	at jcs.o(PG:406)
E/ExperimentLoader( 3387): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3387): 	at jcs.i(PG:143)
E/ExperimentLoader( 3387): 	at hec.a(PG:42)
E/ExperimentLoader( 3387): 	at hee.a(PG:102)
E/ExperimentLoader( 3387): 	at czr.a(PG:65)
E/ExperimentLoader( 3387): 	at kka.a(PG:108)
E/ExperimentLoader( 3387): 	at czp.a(PG:19176)
E/ExperimentLoader( 3387): 	at czp.a(PG:9081)
E/ExperimentLoader( 3387): 	at czq.run(PG:1686)
E/ExperimentLoader( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3387): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3387): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3387): 	at jdm.a(PG:77)
E/ExperimentLoader( 3387): 	... 15 more
E/ExperimentLoader( 3387): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3387): 	at fal.a(PG:38)
E/ExperimentLoader( 3387): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3387): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 295713, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  819): Killing 2305:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@15ff7575}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
,V/KeepSync( 3588): Connecting to GoogleApiClient
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1819): Handling authorization failure
E/ClientConnectionOperation( 1819): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1819): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1819): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1819): 	... 7 more
,V/KeepSync( 3588): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3588): IOException
E/KeepSync( 3588): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3588): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3588): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3588): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3588): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3588): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3588): 	... 10 more
W/KeepSync( 3588): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 328135, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@15ff7575}
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a319d36}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1234): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1234): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1234): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1234): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1234): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1234): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1234): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3052): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3052): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3052): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3052): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3052): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3052): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3052): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3052): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a319d36}
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3771): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3771): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3771): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 34203(1614KB) AllocSpace objects, 13(773KB) LOS objects, 30% free, 35MB/51MB, paused 1.926ms total 90.127ms
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3618): Soft error,
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
,E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 537328, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82)
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at blb.a(PG:3937)
E/HttpOperation( 3387): 	at czp.a(PG:18188)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125)
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 12 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 14 more
,I/art     ( 1234): Explicit concurrent mark sweep GC freed 55934(2MB) AllocSpace objects, 12(1323KB) LOS objects, 36% free, 27MB/43MB, paused 1.687ms total 69.405ms
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82)
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at hec.a(PG:42)
E/HttpOperation( 3387): 	at hee.a(PG:102)
E/HttpOperation( 3387): 	at czr.a(PG:65)
E/HttpOperation( 3387): 	at kka.a(PG:108)
E/HttpOperation( 3387): 	at czp.a(PG:19176)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125)
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 15 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 17 more
,E/ExperimentLoader( 3387): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): 	at jdm.a(PG:82)
E/ExperimentLoader( 3387): 	at jcs.o(PG:406)
E/ExperimentLoader( 3387): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3387): 	at jcs.i(PG:143)
E/ExperimentLoader( 3387): 	at hec.a(PG:42)
E/ExperimentLoader( 3387): 	at hee.a(PG:102)
E/ExperimentLoader( 3387): 	at czr.a(PG:65)
E/ExperimentLoader( 3387): 	at kka.a(PG:108)
E/ExperimentLoader( 3387): 	at czp.a(PG:19176)
E/ExperimentLoader( 3387): 	at czp.a(PG:9081)
E/ExperimentLoader( 3387): 	at czq.run(PG:1686)
E/ExperimentLoader( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3387): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3387): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3387): 	at jdm.a(PG:77)
E/ExperimentLoader( 3387): 	... 15 more
E/ExperimentLoader( 3387): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3387): 	at fal.a(PG:38)
E/ExperimentLoader( 3387): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3387): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 573359, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/KeepSync( 3588): Connecting to GoogleApiClient
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1819): Handling authorization failure
E/ClientConnectionOperation( 1819): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1819): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1819): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1819): 	... 7 more
,V/KeepSync( 3588): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3588): IOException
E/KeepSync( 3588): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3588): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3588): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3588): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3588): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3588): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3588): 	... 10 more
W/KeepSync( 3588): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 609081, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3e8da5d5}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=15.00 rxSuccessRate=20.75 targetRoamBSSID=any RSSI=-47
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3e8da5d5}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659430163
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/kickstart(  870): STATUS: Received file 'm9kefs2',
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.985789 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3771): [406] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3771): [406] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3771): [406] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3e8da5d5}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=8.75 rxSuccessRate=27.44 targetRoamBSSID=any RSSI=-47
,W/bt-btm  ( 2395): Stopping oneshot timer
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3e8da5d5}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/GCM     ( 1819): Message from null null
E/GCM     ( 1819): Dropping message from null
,D/GCM     ( 1234): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/art     (  819): Explicit concurrent mark sweep GC freed 44853(2MB) AllocSpace objects, 15(428KB) LOS objects, 30% free, 35MB/51MB, paused 1.640ms total 74.723ms
,I/BooksSync( 3618): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3618): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3618): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): Soft error,
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3618): Sync error
E/BooksSync( 3618): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3618): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3618): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1027253, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82)
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at blb.a(PG:3937)
E/HttpOperation( 3387): 	at czp.a(PG:18188)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125)
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 12 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 14 more
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3387): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3387): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3387): 	at jdm.a(PG:82)
E/HttpOperation( 3387): 	at jcs.o(PG:406)
E/HttpOperation( 3387): 	at jcn.a(PG:1379)
E/HttpOperation( 3387): 	at jcs.i(PG:143)
E/HttpOperation( 3387): 	at hec.a(PG:42)
E/HttpOperation( 3387): 	at hee.a(PG:102)
E/HttpOperation( 3387): 	at czr.a(PG:65)
E/HttpOperation( 3387): 	at kka.a(PG:108)
E/HttpOperation( 3387): 	at czp.a(PG:19176)
E/HttpOperation( 3387): 	at czp.a(PG:9081)
E/HttpOperation( 3387): 	at czq.run(PG:1686)
E/HttpOperation( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3387): 	at jdj.a(PG:4091)
E/HttpOperation( 3387): 	at jdj.a(PG:1125)
E/HttpOperation( 3387): 	at jdm.a(PG:77)
E/HttpOperation( 3387): 	... 15 more
E/HttpOperation( 3387): Caused by: faj: BadAuthentication
E/HttpOperation( 3387): 	at fal.a(PG:38)
E/HttpOperation( 3387): 	at jdj.a(PG:4089)
E/HttpOperation( 3387): 	... 17 more
E/ExperimentLoader( 3387): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3387): 	at jdm.a(PG:82)
E/ExperimentLoader( 3387): 	at jcs.o(PG:406)
E/ExperimentLoader( 3387): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3387): 	at jcs.i(PG:143)
E/ExperimentLoader( 3387): 	at hec.a(PG:42)
E/ExperimentLoader( 3387): 	at hee.a(PG:102)
E/ExperimentLoader( 3387): 	at czr.a(PG:65)
E/ExperimentLoader( 3387): 	at kka.a(PG:108)
E/ExperimentLoader( 3387): 	at czp.a(PG:19176)
E/ExperimentLoader( 3387): 	at czp.a(PG:9081)
E/ExperimentLoader( 3387): 	at czq.run(PG:1686)
E/ExperimentLoader( 3387): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3387): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3387): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3387): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3387): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3387): 	at jdm.a(PG:77)
E/ExperimentLoader( 3387): 	... 15 more
E/ExperimentLoader( 3387): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3387): 	at fal.a(PG:38)
E/ExperimentLoader( 3387): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3387): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1099456, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,V/KeepSync( 3588): Connecting to GoogleApiClient
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1819): Handling authorization failure
E/ClientConnectionOperation( 1819): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1819): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1819): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1819): ,	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1819): 	... 7 more
,V/KeepSync( 3588): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3588): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3588): IOException
E/KeepSync( 3588): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3588): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3588): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3588): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3588): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3588): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3588): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3588): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3588): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3588): 	... 10 more
W/KeepSync( 3588): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1140413, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/UsageStatsService(  819): User[0] Flushing usage stats to disk
,I/art     ( 1234): Explicit concurrent mark sweep GC freed 64791(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 2.264ms total 69.838ms
,V/GoogleAuthProtoRequest( 3771): [407] a.<init>: mAccountName set to: thalitester@gmail.com
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa4635}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=3.94 rxSuccessRate=23.36 targetRoamBSSID=any RSSI=-47
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3771): [407] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3771): [407] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3771): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3771): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3771): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3771): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3771): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa4635}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa4635}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=2.23 rxSuccessRate=23.84 targetRoamBSSID=any RSSI=-47
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa4635}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/art     (  819): Explicit concurrent mark sweep GC freed 49563(2MB) AllocSpace objects, 16(444KB) LOS objects, 30% free, 35MB/51MB, paused 1.535ms total 93.257ms
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3ae3db85}
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3ae3db85}
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  819): Prepared write state in 21ms
,I/ProcessStatsService(  819): Prepared write state in 7ms
,I/ProcessStatsService(  819): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-50.bin
,W/bt-btm  ( 2395): Stopping oneshot timer
,I/EventLogService( 1819): Opted in for usage reporting
,I/EventLogService( 1819): Aggregate from 1449056357944 (log), 1449056357944 (data)
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa4635}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.56 rxSuccessRate=19.71 targetRoamBSSID=any RSSI=-47
,I/art     ( 1819): Explicit concurrent mark sweep GC freed 15106(1060KB) AllocSpace objects, 5(80KB) LOS objects, 35% free, 29MB/45MB, paused 1.210ms total 55.031ms
,I/GLSUser ( 1234): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1234): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1234): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1234): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1234): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1819): Unknown tag: snet_gcore
W/EventLogAggregator( 1819): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1819): dumping service [account]
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa4635}
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/GCM     ( 1234): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,I/ActivityManager(  819): Killing 3331:com.google.android.gms.wearable/u0a11 (adj 11): empty for 1823s
,I/ActivityManager(  819): Killing 3511:com.android.musicfx/u0a18 (adj 13): empty for 1823s
,I/ActivityManager(  819): Killing 3489:com.google.android.partnersetup/u0a16 (adj 13): empty for 1823s
,I/ActivityManager(  819): Killing 2737:android.process.acore/u0a5 (adj 13): empty for 1823s
,I/ActivityManager(  819): Killing 3238:com.android.providers.calendar/u0a3 (adj 13): empty for 1832s
,I/ActivityManager(  819): Killing 3283:com.google.android.music:main/u0a66 (adj 15): empty for 1853s
,I/ActivityManager(  819): Killing 2964:com.google.android.talk/u0a61 (adj 15): empty for 1855s
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2395): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
