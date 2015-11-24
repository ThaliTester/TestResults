#### Test 513350282ff9e94_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
D/AndroidRuntime( 3761): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3761): CheckJNI is OFF
D/AndroidRuntime( 3761): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{318122d7 token=Token{1ec4c256 ActivityRecord{22a34471 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
I/MicrophoneInputStream( 1534): mic_close com.google.android.apps.gsa.speech.audio.u@1bc59e34
I/HotwordDetector( 1534): Closing mic
D/AndroidRuntime( 3761): Shutting down VM
V/WindowManager(  823): Adding window Window{31735c30 u0 Starting com.test.thalitest} at 3 of 8 (after Window{38ba5920 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  823): Start proc 3775:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1534): Stopping hotword detection.
I/HotwordRecognitionRnr( 1534): Hotword detection finished
I/ActivityManager(  823): Killing 3074:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3252:com.google.android.apps.photos/u0a71 (adj 15): empty #18
,I/WebViewFactory( 3775): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3775): Time to load native libraries: 2 ms (timestamps 8517-8519)
I/LibraryLoader( 3775): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3775): Binding Chromium to main looper Looper (main, tid 1) {2f6cc866}
,I/LibraryLoader( 3775): Expected native library version number "",actual native library version number ""
,I/chromium( 3775): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660781843
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/BrowserStartupController( 3775): Initializing chromium process, singleProcess=true
,W/art     ( 3775): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3775): ApplicationContext is null in ApplicationStatus
,W/chromium( 3775): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3775): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3775): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3775): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  877): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_lock
,D/BluetoothManagerService(  823): Message: 20
,D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dee3160:true
,E/kickstart(  877): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  877): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,W/art     ( 3775): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3775): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3775): CordovaWebView is running on device made by: motorola
,W/art     ( 3775): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3775): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3775): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3775): Validating map...
,V/WindowManager(  823): Adding window Window{3320b290 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{31735c30 u0 Starting com.test.thalitest})
,W/chromium( 3775): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3775): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3775): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +897ms (total +1m46s286ms)
,I/Keyboard.Facilitator( 1222): onFinishInput()
,W/BindingManager( 3775): Cannot call determinedVisibility() - never saw a connection for the pid: 3775
,D/JsMessageQueue( 3775): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3775): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576390400
D/JX-Cordova( 3775): jxcore cordova android initializing
,I/kickstart(  877): STATUS: Received file 'm9kefs2'
I/kickstart(  877): STATUS: 950272 bytes transferred in 0.997417 seconds
I/kickstart(  877): STATUS: Successfully downloaded files from target 
,I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  877): STATUS: Sahara protocol completed
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2909): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2909): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2909): [1] 5.onFinished: Scheduling replication attempt 3.
,W/jxcore-log( 3775): Initializing JXcore engine
W/jxcore-log( 3775): JXcore engine is ready
,W/jxcore-log( 3775): Starting JXcore engine
,W/.test.thalitest( 3775): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12558]" dev="sockfs" ino=12558 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3775): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3775): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9683]" dev="sockfs" ino=9683 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3775): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[23610]" dev="sockfs" ino=23610 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3775): Platform android
W/jxcore-log( 3775): 
W/jxcore-log( 3775): Process ARCH arm
W/jxcore-log( 3775): 
,I/jxcore-log( 3775): JXcore Cordova bridge is ready!
I/jxcore-log( 3775): 
W/jxcore-log( 3775): JXcore engine is started
,I/Choreographer( 3775): Skipped 132 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3775): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3775): Toggling radios to true
I/jxcore-log( 3775): 
,D/BluetoothAdapter( 3775): enable(): BT is already enabled..!
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=4.05 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3775): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): my name is : motorola-Nexus 6_PT5587
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): attempting to connect to test coordinator
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): check test folder
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): found test : ./testFindPeers.js
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): found test : ./testReConnect.js
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): found test : ./testSendData.js
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Test app app.js loaded
I/jxcore-log( 3775): 
,I/Choreographer( 3775): Skipped 116 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3775): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): BLE supported!!
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2909): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2909): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2909): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.78 rxSuccessRate=2.78 targetRoamBSSID=any RSSI=-43
,E/WifiStateMachine(  823): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (243 us)
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  823): Excessive delay in setPowerMode(): 286ms
,I/DreamManagerService(  823): Entering dreamland.
,I/PowerManagerService(  823): Dozing...
I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 11
,E/native  (  823): do suspend false,
,V/KeepSync( 3684): Connecting to GoogleApiClient
,I/art     (  823): Explicit concurrent mark sweep GC freed 42094(2MB) AllocSpace objects, 15(334KB) LOS objects, 32% free, 33MB/49MB, paused 2.511ms total 81.686ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Keyboard.Facilitator( 1222): onFinishInput(),
V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  823): cancelDelayedScan -> 13,
E/native  (  823): do suspend true
,E/ClientConnectionOperation( 1831): Handling authorization failure,
E/ClientConnectionOperation( 1831): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1831): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1831): Caused by: com.google.android.gms.auth.ad: BadAuthentication,
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
,E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1831): 	... 7 more
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,V/KeepSync( 3684): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3684): IOException
E/KeepSync( 3684): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3684): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3684): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3684): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3684): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3684): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3684): 	... 10 more
W/KeepSync( 3684): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 163918, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 164109, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Start proc 3856:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/VacuumService( 1504): Vacuum at: now=1448365678157 tag=VacuumService
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1504): Explicit concurrent mark sweep GC freed 39354(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.713ms total 41.089ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GoogleAuthProtoRequest( 3856): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,D/Finsky  ( 2909): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2909): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2909): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3856): [406] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GoogleURLConnFactory( 1504): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3856): [406] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3856): [406] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,E/Uploader( 1504): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1504): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1504): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1504): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,E/Uploader( 1504): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1504): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1504): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1504): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1504): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1504): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1504): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1504): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504): No account for auth token provided
,W/Uploader( 1504):  no longer exists, so no auth token.
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1504): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1504): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1504): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1504): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1504): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1504): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1504): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1504): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1504): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1504): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  823): Killing 3421:com.google.android.gm/u0a78 (adj 15): empty #17
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/BooksSync( 3714): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3714): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  823): Explicit concurrent mark sweep GC freed 37744(1743KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 2.605ms total 97.060ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3714): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3714): Soft error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3714): Sync error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3714): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 166329, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2909): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2909): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2909): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3775): 
,V/GoogleAuthProtoRequest( 3856): [407] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [407] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [407] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1222): run()
I/Keyboard.Facilitator( 1222): flushDynamicLanguageModels()
,I/ConfigService( 1504): onCreate
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/ConfigService( 1504): onDestroy
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,V/KeepSync( 3684): Connecting to GoogleApiClient
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1831): Handling authorization failure
E/ClientConnectionOperation( 1831): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1831): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1831): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1831): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1831): ,	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.c.b(SourceFile:109),
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1831): 	... 7 more
,V/KeepSync( 3684): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3684): IOException
E/KeepSync( 3684): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3684): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3684): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3684): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3684): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3684): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3684): 	... 10 more
W/KeepSync( 3684): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 286274, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector connect called
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Coordinator is now connected to the server!
I/jxcore-log( 3775): 
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3856): [408] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3856): [409] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [408] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [408] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3856): [409] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3856): [409] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/art     ( 1504): Explicit concurrent mark sweep GC freed 76855(4MB) AllocSpace objects, 9(761KB) LOS objects, 36% free, 28MB/44MB, paused 1.610ms total 62.523ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
,E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 287434, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3856): [410] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3856): [410] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [410] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@6244176}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
,I/art     (  823): Explicit concurrent mark sweep GC freed 31763(1393KB) AllocSpace objects, 10(725KB) LOS objects, 32% free, 33MB/49MB, paused 2.616ms total 76.831ms
,I/BooksSync( 3714): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3714): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3714): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3714): Soft error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3714): Sync error,
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3714): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 319603, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@6244176}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1504): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1504): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1504): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1504): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1504): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1504): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1504): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2909): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2909): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2909): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2909): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2909): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2909): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2909): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2909): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector command called
I/jxcore-log( 3775): 
I/jxcore-log( 3775): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":16,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0}]}
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Start now : testSendData.js,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): stop tests now !
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 16
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): check server
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): serverPort is 37456
I/jxcore-log( 3775): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3775): Stoping All
,I/        ( 3775): Stopping services
I/        ( 3775): Stop Bluetooth
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3775): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3775):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3775): All stuff available and enabled
,D/WifiService(  823): New client listening to asynchronous messages
I/        ( 3775): Stoping All
I/        ( 3775): Stopping services
,I/        ( 3775): Stop Bluetooth
I/        ( 3775): Starting All
I/        ( 3775): Stopping services
I/        ( 3775): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@37019360
I/        ( 3775): Stopping services
,I/        ( 3775): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3775): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3775): peerDiscoveryTimer timeout value:7463
,I/        ( 3775): Stop Bluetooth
,I/        ( 3775): StartBluetooth listener
,I/        ( 3775): StartBluetooth listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 3775): starting to listen
I/BTListenerThread( 3775): waiting to accept incoming Connection,
,I/jxcore-log( 3775): StartBroadcasting started ok
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:51:53.175Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:51:53.176Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:51:53.177Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Connecting to null, at 08:EC:A9:50:75:41
,I/jxcore-log( 3775): 2015-11-24T11:51:53.193Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3775): 
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3775): We already were running, thus doing nothing
,I/        ( 3775): Added local service
I/        ( 3775): Cleared service requests
I/        ( 3775): Stopped peer discovery
I/        ( 3775): Started peer discovery
I/        ( 3775): Discovery state changed to Started.
,W/bt-btif ( 2212): info:x10,
,D/        ( 2212): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5,
W/bt-btif ( 2212): invalid rfc slot id: 5
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:51:55.755Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:51:55.756Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:51:55.758Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 08:EC:A9:50:75:41 newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,V/GoogleAuthProtoRequest( 3856): [411] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [411] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [411] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3775): Found 1 peers.
I/SS      ( 3775): Peer(1): Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3775): 2015-11-24T11:52:00.759Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:00.761Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5271","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5271","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT5271, peerAddress: 90:E7:C4:F6:69:77
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT5271, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3775): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT1208, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT1208, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3775): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT6558, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT6558, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T11:52:05.770Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:05.770Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:05.772Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:05.773Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config( 2212): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1,
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 08:EC:A9:50:75:41
,I/ActivityManager(  823): Start proc 3967:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.,
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : samsung-SM-A300FU_PT884
I/HS      ( 3775): Hand Shake finished outgoing for : samsung-SM-A300FU_PT884
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, samsung-SM-A300FU_PT884
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket,
,D/BluetoothManagerService(  823): Message: 20
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b8ad7d3:true
I/ActivityManager(  823): Killing 2815:com.google.android.talk/u0a61 (adj 15): empty #17
I/BtToRequestSocket( 3775): mHTTPPort  set to : 49091
I/BtConnectorHelper( 3775): Request socket is using : 49091
,I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :49091
,I/jxcore-log( 3775): 2015-11-24T11:52:11.921Z SendDataConnector.js: CLIENT connected to 49091, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:11.922Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 49091
,I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:52:11.933Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): rin ended ---------------------------;
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3775): 2015-11-24T11:52:12.254Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:52:12.358Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3775): 2015-11-24T11:52:12.404Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:12.848Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3775): 2015-11-24T11:52:15.473Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3775): Found 3 peers.
I/SS      ( 3775): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3775): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3775): 2015-11-24T11:52:19.616Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.225Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.300Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.401Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.481Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.482Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.488Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.489Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
,I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3775): 2015-11-24T11:52:20.499Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3775): 
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3775): ---- round done--------
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.503Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:20.503Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:20.503Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: 00:F4:6F:30:E0:6C, name: null,
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback,
,I/        ( 3775): Connecting to null, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 27309 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63),
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4aeb4 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4aeb4 rs_disc_pending=1,
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b07c rs_disc_pending=1,
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f298a09:true
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: A3-1
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GoogleAuthProtoRequest( 3856): [412] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [412] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [412] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	,at com.google.android.gms.gcm.c.run(Unknown Source),
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c,
,W/bt-btif ( 2212): invalid rfc slot id: 7
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 2212): No record of the device:null
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 00:F4:6F:30:E0:6C newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list,
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:52:27.969Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:27.970Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:27.970Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3775): Found 4 peers.
I/SS      ( 3775): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3775): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7476","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7476","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7476, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7476, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3775): 2015-11-24T11:52:32.972Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:32.973Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:37.978Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:37.979Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:37.980Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:37.980Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config( 2212): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2212): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : samsung-SM-G800F_PT1208
I/HS      ( 3775): Hand Shake finished outgoing for : samsung-SM-G800F_PT1208
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, samsung-SM-G800F_PT1208
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 55945
,I/BtConnectorHelper( 3775): Request socket is using : 55945
I/BtToRequestSocket( 3775): Now accepting connections
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :55945
,I/jxcore-log( 3775): 2015-11-24T11:52:39.714Z SendDataConnector.js: CLIENT connected to 55945, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:39.716Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 55945
I/BtToRequestSocket( 3775): Set local streams,
I/BtToRequestSocket( 3775): rin ended ---------------------------;
I/jxcore-log( 3775): 2015-11-24T11:52:39.727Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 3775): 2015-11-24T11:52:39.886Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.000Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.066Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.128Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.191Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.234Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.297Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.365Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.445Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.477Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.478Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:40.485Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:40.485Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3775): 2015-11-24T11:52:40.492Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:40.497Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:40.497Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T11:52:40.499Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/        ( 3775): Selected device address: 08:EC:A9:50:76:27, name: null,
,I/BTConnectToThread( 3775): Starting to connect,
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 08:EC:A9:50:76:27
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 19976 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 9
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:52:45.643Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:45.644Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:45.645Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 8 peers.
,I/SS      ( 3775): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3775): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3775): 2015-11-24T11:52:50.647Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:50.648Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5271","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5271","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT5271, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT5271, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3775): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT1208, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT1208, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3775): 2015-11-24T11:52:55.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:52:55.653Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T11:52:55.654Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:52:55.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b40c rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config( 2212): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3775): we got incoming connection
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTListenerThread( 3775): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3775): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT3120
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, HTC-HTC One_M8_PT3120
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.,
I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:53:00.084Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.586Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.594Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.603Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.607Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.610Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.616Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.680Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.716Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.724Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.729Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:00.790Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.163Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.170Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.175Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.182Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.355Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.364Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.371Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.377Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.384Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.424Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.444Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.451Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.457Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.463Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.494Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.596Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.634Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.700Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.734Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/SS      ( 3775): Found 7 peers.,
I/SS      ( 3775): Peer(1): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3775): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3775): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/jxcore-log( 3775): 2015-11-24T11:53:01.794Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.801Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.811Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.820Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.854Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.920Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:01.924Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 4
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT3120
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in,
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT3120,
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Close bt socket
I/jxcore-log( 3775): 2015-11-24T11:53:02.042Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x4d
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0,
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: HTC One_M8
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 8 peers.
,I/SS      ( 3775): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_608e 92:e7:c4:e6:4c:f8
,I/SS      ( 3775): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Peer(7): S5mini-1 02:f4:6f:30:e0:6d,
,I/SS      ( 3775): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 10
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:53:28.195Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:28.197Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:28.199Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3775): Found 9 peers.
,I/SS      ( 3775): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3775): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3775): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/jxcore-log( 3775): 2015-11-24T11:53:33.202Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:33.203Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:38.206Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:38.207Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:38.208Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:38.209Z SendDataConnector.js: do connect now
,I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3650","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3650","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT3650, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT3650, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 12
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:53:43.369Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:43.369Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:43.370Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:48.371Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:48.372Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,V/KeepSync( 3684): Connecting to GoogleApiClient
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1831): Handling authorization failure,
E/ClientConnectionOperation( 1831): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1831): 	at java.lang.Thread.run(Thread.java:818),
E/ClientConnectionOperation( 1831): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1831): 	... 7 more
,V/KeepSync( 3684): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3684): IOException
E/KeepSync( 3684): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3684): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3684): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3684): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3684): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3684): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3684): 	... 10 more
W/KeepSync( 3684): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 530875, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/jxcore-log( 3775): 2015-11-24T11:53:53.376Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:53.377Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:53.378Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:53.378Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 08:EC:A9:50:76:27, name: null,
,I/        ( 3775): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,V/GoogleAuthProtoRequest( 3856): [413] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  823): Explicit concurrent mark sweep GC freed 35214(1649KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.629ms total 72.404ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [413] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3856): [413] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 13
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:53:58.539Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:53:58.540Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:53:58.540Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3775): Found 7 peers.
,I/SS      ( 3775): Peer(1): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3775): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/jxcore-log( 3775): 2015-11-24T11:54:03.542Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:03.543Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3650","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3650","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT3650, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT3650, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3775): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1208"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT1208, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT1208, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3775): 2015-11-24T11:54:08.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:08.547Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:08.548Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:08.548Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 14
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:54:13.700Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:13.701Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:13.702Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:13.703Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:13.705Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:13.706Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T11:54:13.706Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): ,
I/        ( 3775): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 80:01:84:8A:B3:68
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 93204 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/SS      ( 3775): Found 5 peers.
I/SS      ( 3775): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 15
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:54:36.222Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:36.223Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:36.224Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3775): 2015-11-24T11:54:41.225Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:41.226Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3775): Found 6 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 3775): 2015-11-24T11:54:46.232Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:46.232Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:46.234Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:46.236Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 80:01:84:8A:B3:68
D/WifiP2pManager( 3775): Ignored { when=-22ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3775): Started service discovery
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config( 2212): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 80:01:84:8A:B3:68
I/BluetoothBondStateMachine( 2212): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3775): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : HTC-HTC Desire 820_PT9302
I/HS      ( 3775): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9302
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9302
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3775): mHTTPPort  set to : 32788
I/BtConnectorHelper( 3775): Request socket is using : 32788
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :32788
,I/jxcore-log( 3775): 2015-11-24T11:54:48.264Z SendDataConnector.js: CLIENT connected to 32788, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:48.265Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 32788
,I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:54:48.273Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): rin ended ---------------------------;
,I/EventLogService( 1831): Opted in for usage reporting
,I/EventLogService( 1831): Aggregate from 1448364252748 (log), 1448364252748 (data)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,W/EventLogAggregator( 1831): Unknown tag: snet_gcore
W/EventLogAggregator( 1831): Unknown tag: snet_launch_service
,I/art     ( 1504): Explicit concurrent mark sweep GC freed 54820(2MB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 27MB/43MB, paused 1.053ms total 28.243ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ServiceDumpSys( 1831): dumping service [account]
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): 	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176)
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 562407, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3775): 2015-11-24T11:54:49.120Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.386Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.390Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.464Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.517Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.564Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.612Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.645Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.651Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.683Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.683Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:49.687Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:49.688Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 80:01:84:8A:B3:68
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
,I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3775): 2015-11-24T11:54:49.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:49.702Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:49.702Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:49.703Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 35979 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b5d4 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/btif_config( 2212): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2212): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2212): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [50:2e:6c:ac:21:50]: 0, 0, 0
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: HTC Desire 820
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3775): we got incoming connection
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b40c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : HTC-HTC One_M8_PT3120
I/HS      ( 3775): Hand Shake finished outgoing for : HTC-HTC One_M8_PT3120
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, HTC-HTC One_M8_PT3120
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 56426
,I/BtConnectorHelper( 3775): Request socket is using : 56426
I/BtToRequestSocket( 3775): Now accepting connections
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3775): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
I/HS      ( 3775): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT9877
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, LGE-Nexus 5_PT9877
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
,I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456,
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:54:54.350Z SendDataTCPServer.js: TCP/IP server connected
,I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :56426
,I/jxcore-log( 3775): 2015-11-24T11:54:54.574Z SendDataConnector.js: CLIENT connected to 56426, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.575Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 56426
,I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:54:54.583Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
I/BtToRequestSocket( 3775): rin ended ---------------------------;
,I/jxcore-log( 3775): 2015-11-24T11:54:54.750Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.777Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.781Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.806Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.810Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.845Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.851Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3775): 2015-11-24T11:54:54.886Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.892Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.896Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.905Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.925Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.954Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.969Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:54.975Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3775): 2015-11-24T11:54:54.987Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.009Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.045Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.050Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.084Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.107Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.112Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.127Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.144Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.147Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.156Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.161Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.201Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.235Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.262Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.294Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.330Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3775): 2015-11-24T11:54:55.359Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.364Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.385Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.425Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.494Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.603Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 11
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT9877
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
,I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT9877
,I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/jxcore-log( 3775): 2015-11-24T11:54:55.614Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.655Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.714Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.808Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:54:55.903Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:55.904Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T11:54:55.908Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:55.908Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3775): 2015-11-24T11:54:55.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:55.923Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:55.923Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:54:55.923Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): ,
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 6202 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp,
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 19
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:54:58.204Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:58.205Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:54:58.206Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: HTC One_M8
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T11:55:03.214Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:03.215Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3775): 2015-11-24T11:55:08.219Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:08.220Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:08.221Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:08.222Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 20
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T11:55:09.433Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:09.434Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:09.435Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:55:14.436Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:14.437Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/BooksSync( 3714): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3714): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3714): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3714): Soft error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3714): Sync error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3714): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 597132, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/jxcore-log( 3775): 2015-11-24T11:55:19.441Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:19.442Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:19.443Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:19.443Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 21
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3775): 2015-11-24T11:55:22.033Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:22.033Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:22.036Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3775): 2015-11-24T11:55:27.037Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:27.038Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
I/        ( 3775): Started service discovery
,I/jxcore-log( 3775): 2015-11-24T11:55:32.042Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:32.043Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:32.044Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:32.044Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 22
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:55:33.273Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:33.274Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:33.274Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:55:38.276Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:38.278Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): ,
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config( 2212): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2212): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3775): we got incoming connection
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTListenerThread( 3775): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3775): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT4343
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, samsung-SM-N9005_PT4343
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:55:39.791Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.179Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.182Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.203Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.207Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.210Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.219Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.265Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.305Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.308Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.343Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.376Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.418Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.427Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.436Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.439Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.444Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.484Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.492Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.496Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.536Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.543Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.597Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.635Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.642Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:40.673Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 18
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4343
I/BtToSocketBase( 3775): Stop ReceivingThread
,I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
,I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4343
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 3775): 2015-11-24T11:55:40.730Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:43.283Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:43.284Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:43.285Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:43.285Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bb2c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bb2c rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 24
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:55:45.093Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:45.094Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:45.098Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:45.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:45.106Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:45.107Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:45.107Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 49171 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 25
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:55:45.732Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:45.733Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:45.734Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:55:50.736Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:50.736Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3775): 2015-11-24T11:55:55.740Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:55.741Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:55.742Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:55:55.742Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 26
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:55:58.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:58.783Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:55:58.784Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/jxcore-log( 3775): 2015-11-24T11:56:03.785Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:03.785Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:08.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:08.789Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:08.790Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:08.790Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 27
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:56:10.340Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:10.341Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:10.342Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config( 2212): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3775): we got incoming connection
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTListenerThread( 3775): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
I/HS      ( 3775): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT4523
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, samsung-SM-G900F_PT4523
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
,I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/jxcore-log( 3775): 2015-11-24T11:56:13.180Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:56:13.610Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.616Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.636Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.643Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.652Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.668Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.704Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.708Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.711Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.717Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.730Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.764Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.794Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.834Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.938Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.993Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:13.997Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:56:14.075Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.114Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.141Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:56:14.236Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.243Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.274Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.318Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.375Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.390Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.394Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.447Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.484Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.524Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.527Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.534Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.573Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.657Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.663Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.700Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.705Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.734Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:14.773Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 23
I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT4523
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3775): 2015-11-24T11:56:14.903Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3775): 2015-11-24T11:56:15.344Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:15.346Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: S5-1,
,I/jxcore-log( 3775): 2015-11-24T11:56:20.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:20.350Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:20.351Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:20.352Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null,
,I/BTConnectToThread( 3775): Starting to connect,
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 610c
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 29
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:56:21.118Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:21.119Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:21.120Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:56:26.121Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:26.122Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,V/GoogleAuthProtoRequest( 3856): [414] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [414] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [414] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery,
,I/jxcore-log( 3775): 2015-11-24T11:56:31.126Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:31.127Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:31.127Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:31.128Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d,
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 30
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:56:32.842Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:32.843Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:32.848Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:32.852Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:32.857Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:32.857Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:32.858Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Connecting to null, at F8:95:C7:87:3C:51
I/SS      ( 3775): Found 2 peers.
,I/SS      ( 3775): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 47737 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/        ( 3775): Started service discovery
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c084 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp,
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config( 2212): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : LGE-LG-H815_PT1012
I/HS      ( 3775): Hand Shake finished outgoing for : LGE-LG-H815_PT1012
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, LGE-LG-H815_PT1012
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 44267
I/BtConnectorHelper( 3775): Request socket is using : 44267
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :44267
,I/jxcore-log( 3775): 2015-11-24T11:56:37.318Z SendDataConnector.js: CLIENT connected to 44267, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.319Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 44267
,I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:56:37.327Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
I/BtToRequestSocket( 3775): rin ended ---------------------------;
,I/jxcore-log( 3775): 2015-11-24T11:56:37.528Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.626Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.662Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.669Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.704Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.745Z SendDataConnector.js: CLIENT is data received : 60000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.752Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.788Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.823Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.883Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:37.884Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.890Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:37.892Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
,I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close bt in
,I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3775): 2015-11-24T11:56:37.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:37.903Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:37.903Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
I/jxcore-log( 3775): 2015-11-24T11:56:37.903Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 5028 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 32
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:56:43.044Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:43.046Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:43.047Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/jxcore-log( 3775): 2015-11-24T11:56:48.048Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:48.049Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 3 peers.
,I/SS      ( 3775): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3775): 2015-11-24T11:56:53.053Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:53.054Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:53.054Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:53.055Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config( 2212): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2212): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2212): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : motorola-XT1039_PT2208
I/HS      ( 3775): Hand Shake finished outgoing for : motorola-XT1039_PT2208
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, motorola-XT1039_PT2208
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 47594
,I/BtConnectorHelper( 3775): Request socket is using : 47594
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :47594
,I/jxcore-log( 3775): 2015-11-24T11:56:56.328Z SendDataConnector.js: CLIENT connected to 47594, error: null
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:56.329Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 47594
,I/BtToRequestSocket( 3775): Set local streams
I/BtToRequestSocket( 3775): rin ended ---------------------------;
,I/jxcore-log( 3775): 2015-11-24T11:56:56.337Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:20888
,I/jxcore-log( 3775): 2015-11-24T11:56:56.509Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22999
,I/jxcore-log( 3775): 2015-11-24T11:56:56.589Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3775): 2015-11-24T11:56:56.602Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:56.689Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3775): ,
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6169
,I/jxcore-log( 3775): 2015-11-24T11:56:56.733Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:56:56.919Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:56.944Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:56.987Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:57.114Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:57.169Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:57.170Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:57.178Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:57.178Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3775): 2015-11-24T11:56:57.188Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:56:57.193Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:57.194Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:56:57.194Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/        ( 3775): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 44:80:EB:7B:5A:05,
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 19267 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c24c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c24c rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2212): onReceive,
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2212): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 34
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T11:57:02.522Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:02.523Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:02.524Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3775): Found 4 peers.
I/SS      ( 3775): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery,
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3775): 2015-11-24T11:57:07.525Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:07.526Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:12.530Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:12.531Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:12.532Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:12.532Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3775): Starting to connect,
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 44:80:EB:7B:5A:05
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config( 2212): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : motorola-XT1072_PT6558
,I/HS      ( 3775): Hand Shake finished outgoing for : motorola-XT1072_PT6558
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, motorola-XT1072_PT6558
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 39150
,I/BtConnectorHelper( 3775): Request socket is using : 39150
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :39150
,I/jxcore-log( 3775): 2015-11-24T11:57:14.828Z SendDataConnector.js: CLIENT connected to 39150, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:14.829Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 39150
,I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:57:14.836Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
I/BtToRequestSocket( 3775): rin ended ---------------------------;
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4504
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22999
,I/jxcore-log( 3775): 2015-11-24T11:57:14.926Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.007Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3775): 2015-11-24T11:57:15.193Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.429Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3775): 2015-11-24T11:57:15.450Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 4 peers.
,I/SS      ( 3775): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/jxcore-log( 3775): 2015-11-24T11:57:15.597Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.645Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.770Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.775Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.815Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.816Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.821Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:15.822Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3775): Stop ReceivingThread
,I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3775): 2015-11-24T11:57:15.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:15.846Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:15.847Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:15.848Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3775): Connecting to null, at 7C:F9:0E:37:96:AB
I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 18624 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Started service discovery
,D/btif_config( 2212): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.,
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTConnectToThread( 3775): HandshakeOk : samsung-SM-A500FU_PT3421
,I/HS      ( 3775): Hand Shake finished outgoing for : samsung-SM-A500FU_PT3421
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, samsung-SM-A500FU_PT3421
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3775): mHTTPPort  set to : 50143
I/BtConnectorHelper( 3775): Request socket is using : 50143
I/BtToRequestSocket( 3775): Now accepting connections
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :50143
,I/jxcore-log( 3775): 2015-11-24T11:57:17.213Z SendDataConnector.js: CLIENT connected to 50143, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.214Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 50143,
I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:57:17.225Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): rin ended ---------------------------;
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10308,tx.queue.count:11,available:24707,
,I/jxcore-log( 3775): 2015-11-24T11:57:17.322Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.350Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3775): 2015-11-24T11:57:17.425Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3775): 2015-11-24T11:57:17.479Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.507Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.552Z SendDataConnector.js: CLIENT is data received : 60000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.559Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.611Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.650Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.697Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.697Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.710Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.711Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3775): 2015-11-24T11:57:17.722Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:17.727Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:17.728Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:17.728Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 3775): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 1855 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3775): HandshakeOk : samsung-SM-N9005_PT4343
I/HS      ( 3775): Hand Shake finished outgoing for : samsung-SM-N9005_PT4343
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, samsung-SM-N9005_PT4343
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3775): mHTTPPort  set to : 44120
,I/BtConnectorHelper( 3775): Request socket is using : 44120
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :44120
,I/jxcore-log( 3775): 2015-11-24T11:57:19.046Z SendDataConnector.js: CLIENT connected to 44120, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.046Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 44120
,I/BtToRequestSocket( 3775): Set local streams
I/jxcore-log( 3775): 2015-11-24T11:57:19.054Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): rin ended ---------------------------;
,I/jxcore-log( 3775): 2015-11-24T11:57:19.212Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.264Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.327Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.375Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.415Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.466Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.512Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.569Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.575Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.652Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.653Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:19.657Z SendDataConnector.js: CLIENT Stop now
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:19.658Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
I/BtConnectorHelper( 3775): Disconnect outgoing peer: E0:DB:10:1F:C9:5E,
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread,
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/jxcore-log( 3775): 2015-11-24T11:57:19.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:19.669Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:19.670Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:19.670Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/        ( 3775): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 1926 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: XT1072
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bb2c rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3,
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Nexus 5,
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bb2c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3775): HandshakeOk : LGE-Nexus 5_PT9877
I/HS      ( 3775): Hand Shake finished outgoing for : LGE-Nexus 5_PT9877
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, LGE-Nexus 5_PT9877
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 43765
I/BtConnectorHelper( 3775): Request socket is using : 43765,
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :43765,
,I/jxcore-log( 3775): 2015-11-24T11:57:23.013Z SendDataConnector.js: CLIENT connected to 43765, error: null
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:23.014Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 43765
,I/BtToRequestSocket( 3775): Set local streams
,I/BtToRequestSocket( 3775): rin ended ---------------------------;
,I/jxcore-log( 3775): 2015-11-24T11:57:23.029Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4640
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22145
,I/jxcore-log( 3775): 2015-11-24T11:57:23.330Z SendDataConnector.js: CLIENT is data received : 10000
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.379Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11255
,I/jxcore-log( 3775): 2015-11-24T11:57:23.462Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6305
,I/jxcore-log( 3775): 2015-11-24T11:57:23.473Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.517Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.525Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.572Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.639Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/jxcore-log( 3775): 2015-11-24T11:57:23.809Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Note3-1,
,I/jxcore-log( 3775): 2015-11-24T11:57:23.868Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.869Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:23.872Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:23.873Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
I/BtConnectorHelper( 3775): Disconnect outgoing peer: 34:FC:EF:11:AE:67
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/jxcore-log( 3775): 2015-11-24T11:57:23.878Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3775): 
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:23.880Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3775): 2015-11-24T11:57:23.880Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:23.881Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 4200 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b79c rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c7a4 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Nexus 5
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5
W/bt-btif ( 2212): invalid rfc slot id: 39
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/jxcore-log( 3775): 2015-11-24T11:57:28.404Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:28.404Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:28.406Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 4 peers.
I/SS      ( 3775): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/jxcore-log( 3775): 2015-11-24T11:57:33.407Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:33.408Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT6558, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT6558, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3775): 2015-11-24T11:57:38.412Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:38.413Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:38.413Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:38.414Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect,
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51,
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a0,
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 2212): invalid rfc slot id: 40
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:57:43.394Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:43.394Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:43.396Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [f8:95:c7:87:3c:51]: 6, 10f, 608
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: G4-1
,D/btif_config( 2212): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1,
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2212): Failed to remove device: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3775): we got incoming connection
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTListenerThread( 3775): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3775): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1012
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, LGE-LG-H815_PT1012
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3775): --DoOneRunRound started,
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:57:47.005Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.415Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.419Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.423Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.498Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.506Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.534Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.541Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.574Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.582Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.614Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.835Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.843Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.851Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.859Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.926Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.931Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.978Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.982Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:47.990Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.024Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.029Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.036Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.074Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.077Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:57:48.082Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.114Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:57:48.125Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.131Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.163Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.169Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.175Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.179Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.201Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.233Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.240Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.247Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.255Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.334Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.382Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:57:48.398Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.398Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.460Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T11:57:48.767Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:48.813Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 28
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1012
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3775): 2015-11-24T11:57:48.926Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x4e
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: G4-1
,I/jxcore-log( 3775): 2015-11-24T11:57:53.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:57:53.403Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:53.404Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:53.404Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/BTConnectToThread( 3775): Starting to connect,
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a020c
W/bt-btif ( 2212): invalid rfc slot id: 42
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
,E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/jxcore-log( 3775): 2015-11-24T11:57:57.404Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:57.405Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:57:57.406Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3775): 
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,V/GoogleAuthProtoRequest( 3856): [415] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [415] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [415] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3775): 2015-11-24T11:58:02.408Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:02.408Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/jxcore-log( 3775): 2015-11-24T11:58:07.413Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:07.414Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:07.414Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:07.415Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a0
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
W/bt-btif ( 2212): invalid rfc slot id: 43
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:58:11.404Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:11.405Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/jxcore-log( 3775): 2015-11-24T11:58:11.406Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/jxcore-log( 3775): 2015-11-24T11:58:16.408Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:16.409Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/jxcore-log( 3775): 2015-11-24T11:58:21.413Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:21.414Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:21.415Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:21.415Z SendDataConnector.js: do connect now,
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5
E/bt-btif ( 2212): PORT_StartCnf failed result:5
W/bt-btif ( 2212): invalid rfc slot id: 44
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:58:26.407Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/jxcore-log( 3775): 2015-11-24T11:58:26.409Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3775): 2015-11-24T11:58:26.413Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:26.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:26.423Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:26.423Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:26.423Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 62530 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 45,
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:58:27.303Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:27.306Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:27.306Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/jxcore-log( 3775): 2015-11-24T11:58:32.309Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:32.309Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28,
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T11:58:37.312Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:37.313Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:37.314Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:37.314Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 46
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:58:40.042Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:40.043Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:40.044Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:58:45.045Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:45.046Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:50.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:50.050Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:58:50.051Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:50.051Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  823): Explicit concurrent mark sweep GC freed 50197(2MB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.415ms total 73.695ms
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 47
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:58:53.177Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:53.178Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:53.179Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T11:58:58.181Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:58:58.182Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3775): 2015-11-24T11:59:03.185Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:03.186Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:03.187Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:03.187Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77,
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 48
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:59:04.259Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:04.260Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:04.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3775): 2015-11-24T11:59:09.261Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:09.262Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:14.265Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:14.266Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:14.267Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:14.267Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null,
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 49
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T11:59:18.540Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:18.541Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:18.544Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:18.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 1
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:18.549Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:18.550Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:18.550Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 52118 ms, rnd: 5, ex: Connection to 90:E7:C4:F6:69:77 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c7a4 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [7c:f9:0e:34:8a:a0]: 6, 10f, 608
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3775): Starting to Handshake
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTConnectToThread( 3775): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3775): HandshakeOk : samsung-SM-G900F_PT4523
I/HS      ( 3775): Hand Shake finished outgoing for : samsung-SM-G900F_PT4523
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, samsung-SM-G900F_PT4523
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 52350
,I/BtConnectorHelper( 3775): Request socket is using : 52350
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :52350
,I/jxcore-log( 3775): 2015-11-24T11:59:23.705Z SendDataConnector.js: CLIENT connected to 52350, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:23.708Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:23.717Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 52350
,I/BtToRequestSocket( 3775): Set local streams
I/BtToRequestSocket( 3775): rin ended ---------------------------;
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:539
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T11:59:24.548Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:24.695Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:24.975Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:25.605Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:25.611Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:25.719Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:25.771Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:25.821Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: XT1072
,I/jxcore-log( 3775): 2015-11-24T11:59:26.564Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3775): we got incoming connection
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c414 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3775): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
I/HS      ( 3775): Incoming connection Hand Shake finished for : motorola-XT1072_PT6558
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, motorola-XT1072_PT6558
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:59:27.801Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:27.946Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:27.947Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:27.950Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:27.950Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3775): 
,I/BtConnectorHelper( 3775): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Close localHostSocket,
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToRequestSocket( 3775): Close server socket
I/jxcore-log( 3775): 2015-11-24T11:59:27.960Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3775): 
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3775): ---- round done--------
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:27.963Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:27.963Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:27.963Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 9397 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c414 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3775): 2015-11-24T11:59:28.295Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.307Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.313Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.323Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.326Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.332Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.347Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.384Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.469Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.475Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.607Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.848Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:28.853Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3775): 2015-11-24T11:59:29.056Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T11:59:29.474Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/jxcore-log( 3775): 2015-11-24T11:59:29.849Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:29.897Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:29.903Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:29.927Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:29.936Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:29.943Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:29.984Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.000Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.027Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.033Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.046Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.085Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.090Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.101Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.162Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.169Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.180Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.185Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.224Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.285Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.291Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:59:30.319Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.329Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.364Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.405Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.431Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.460Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.500Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.566Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:30.574Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): info:x10,
,D/        ( 2212): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2212): invalid rfc slot id: 41
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT6558
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3775): 2015-11-24T11:59:30.760Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x4b
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c414 rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/btif_config( 2212): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2212): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothAdapterProperties( 2212): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2212): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2212): StableState(): Entering Off State
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3775): Starting to Handshake,
E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bebc rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
I/BTConnectToThread( 3775): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery,
,I/BTConnectToThread( 3775): got MESSAGE_READ 83 bytes.,
I/BTConnectToThread( 3775): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3775): HandshakeOk : samsung-SM-A300FU_PT4812
I/HS      ( 3775): Hand Shake finished outgoing for : samsung-SM-A300FU_PT4812
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4812
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): mHTTPPort  set to : 35507,
I/BtConnectorHelper( 3775): Request socket is using : 35507
I/BtToRequestSocket( 3775): Now accepting connections
,I/BtConnectorHelper( 3775): Calling ConnectionStatusUpdate with port :35507
,I/jxcore-log( 3775): 2015-11-24T11:59:33.568Z SendDataConnector.js: CLIENT connected to 35507, error: null
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:33.569Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3775): 
,I/BtToRequestSocket( 3775): incoming data from: /127.0.0.1, port: 35507
I/jxcore-log( 3775): 2015-11-24T11:59:33.580Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3775): 
I/BtToRequestSocket( 3775): Set local streams
,I/BtToRequestSocket( 3775): rin ended ---------------------------;
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c414 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,I/jxcore-log( 3775): 2015-11-24T11:59:34.443Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c414 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3775): 2015-11-24T11:59:35.273Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3775): 
,I/        ( 3775): Started service discovery
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/jxcore-log( 3775): 2015-11-24T11:59:35.420Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3775): 
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1534): Bluetooth Device Name: XT1072,
,I/jxcore-log( 3775): 2015-11-24T11:59:35.467Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3775): 
,D/        ( 2212): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3775): 2015-11-24T11:59:35.556Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:35.634Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:59:35.733Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T11:59:35.775Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:35.874Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:35.879Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:35.880Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:35.883Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:35.886Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3775): 
I/BtConnectorHelper( 3775): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3775): Close bt socket
,I/BtToRequestSocket( 3775): Close server socket
,W/bt-btif ( 2212): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
I/jxcore-log( 3775): 2015-11-24T11:59:35.896Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T11:59:35.900Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:35.900Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0,
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:59:35.901Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 7918 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63),
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14),
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 53
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:59:36.757Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:36.758Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:36.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1,
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:,
,I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51,
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3775): 2015-11-24T11:59:41.760Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:41.761Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT6558, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT6558, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3775): 2015-11-24T11:59:46.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:46.766Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:46.766Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:46.767Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect,
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 54
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T11:59:47.698Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:47.698Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:47.699Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [80:01:84:8a:b3:68]: 7, f, 2205
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3775): we got incoming connection
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,I/BTListenerThread( 3775): got MESSAGE_READ 84 bytes.,
,I/BTListenerThread( 3775): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3775): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9302
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9302,
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3775): Creating BTConnectedThread
,I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:59:52.035Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.408Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.412Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.420Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.426Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.429Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.435Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.444Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.485Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.491Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.531Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T11:59:52.563Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.569Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.577Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.615Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.620Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.623Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.653Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.685Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.700Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.701Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.725Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.733Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.774Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.782Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.786Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.823Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.843Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:52.846Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 51
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9302
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3775): Close bt socket
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9302
I/BtToSocketBase( 3775): Close bt in
,I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/jxcore-log( 3775): 2015-11-24T11:59:52.907Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0,
W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x42
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [08:ec:a9:50:75:41]: 7, f, 610c
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: A3-1
,I/jxcore-log( 3775): 2015-11-24T11:59:57.705Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:57.705Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:57.706Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:57.706Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3775): we got incoming connection
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 56
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3775): 2015-11-24T11:59:58.833Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:58.834Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T11:59:58.835Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3775): Found 7 peers.
,I/SS      ( 3775): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3775): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/BTListenerThread( 3775): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
I/HS      ( 3775): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT884
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, samsung-SM-A300FU_PT884
I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T11:59:59.012Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.400Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.407Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.434Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.442Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.474Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.479Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.596Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.602Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.624Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.631Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.669Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T11:59:59.694Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T11:59:59.759Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3775): 
,I/        ( 3775): Started service discovery
,I/jxcore-log( 3775): 2015-11-24T11:59:59.946Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.047Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.213Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.288Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.295Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.300Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T12:00:00.357Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.364Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.470Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.476Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.539Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.545Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.553Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.594Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.617Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.732Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.787Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.793Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.799Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.833Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.971Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.977Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:00.983Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.023Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.045Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.053Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.162Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.224Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.263Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.304Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.311Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.419Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.483Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.489Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:01.493Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 55,
I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT884
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT884
I/BtToSocketBase( 3775): Close LocalOutputStream
,I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
,I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt out
,I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Close bt socket
I/jxcore-log( 3775): 2015-11-24T12:00:01.942Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x43
,W/bt-btm  ( 2212): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b5d4 rs_disc_pending=2
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T12:00:03.835Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:03.836Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: A3-1,
,I/jxcore-log( 3775): 2015-11-24T12:00:08.840Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:08.840Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:08.841Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:08.842Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 58
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:00:09.215Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:09.215Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:09.216Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:00:14.217Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:14.218Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:00:19.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:19.222Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:19.223Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:19.223Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect,
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp,
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 59
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:00:21.450Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:21.452Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:21.459Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T12:00:21.463Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 2
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:21.468Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54,
,I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T12:00:21.468Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54,
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T12:00:21.469Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 45552 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=1,
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 60
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3775): 2015-11-24T12:00:24.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:24.769Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:24.771Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=0,
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:00:29.772Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:29.773Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:34.777Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:34.777Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:34.778Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:34.778Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp,
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 61
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:00:35.549Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:35.550Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:35.550Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:00:40.552Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:40.553Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:45.557Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:45.558Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:45.559Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:45.559Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 62
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:00:46.892Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:46.892Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:46.910Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [f4:f1:e1:5c:3b:e2]: 6, f, 410d
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3775): we got incoming connection
,I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c24c rs_disc_pending=0
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3775): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3775): Incoming connection Hand Shake finished for : motorola-XT1039_PT2208
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, motorola-XT1039_PT2208
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T12:00:48.554Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/ActivityManager(  823): Start proc 4232:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4232): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4232):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4232):   adb logcat -s GAv4
,W/GAv4    ( 4232): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4232): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4232): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 2524:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/jxcore-log( 3775): 2015-11-24T12:00:48.990Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:48.994Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.008Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.023Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.025Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.037Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.093Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.134Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.145Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.185Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.191Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.194Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.245Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.253Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:49.258Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.271Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.304Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.307Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.314Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.354Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.372Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.389Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.446Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.483Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.497Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.534Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
,I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.552Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.598Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.614Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.654Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.663Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:49.694Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 57
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT2208
,I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT2208
,I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
,I/BtToSocketBase( 3775): Close bt in
I/BtToSocketBase( 3775): Close bt in,
I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Close bt out,
I/BtToSocketBase( 3775): Close bt socket
I/jxcore-log( 3775): 2015-11-24T12:00:49.787Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c24c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x4b
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Thali Test (Galaxy A3),
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c24c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
D/GCM     ( 1504): Message class com.google.f.a.a.i
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2212): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2212): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3775): we got incoming connection
I/BTHandshakeSocketThread( 3775): Creating BTHandshakeSocketThread
I/BTListenerThread( 3775): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread started
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3775): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3775): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3775): MESSAGE_WRITE 82 bytes.
I/HS      ( 3775): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT4812
I/BTHandshakeSocketThread( 3775): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3775): Starting the connected thread incoming : true, samsung-SM-A300FU_PT4812
,I/BtToSocketBase( 3775): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3775): Creating BTConnectedThread
I/BtConnectorHelper( 3775): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3775): --DoOneRunRound started
,I/BtToRequestSocket( 3775): LocalHost address: localhost/127.0.0.1, port: 37456
,I/BtToRequestSocket( 3775): --DoOneRunRound ended
,I/jxcore-log( 3775): 2015-11-24T12:00:51.818Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:51.912Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:51.912Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.276Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.314Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.324Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.333Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.336Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.416Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.423Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.454Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.456Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.464Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.474Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.514Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.534Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.551Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.558Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.594Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.601Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.608Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.616Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.653Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.699Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.709Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.744Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.751Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.758Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.778Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.814Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.843Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.852Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.884Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.888Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.895Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.901Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.909Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.944Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.950Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:52.993Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:53.023Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): invalid rfc slot id: 63
,I/BtToSocketBase( 3775): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3775): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT4812
I/BtToSocketBase( 3775): Stop ReceivingThread
I/BtToSocketBase( 3775): Stop SendingThread
,I/BtToSocketBase( 3775): Close local in
I/BtToSocketBase( 3775): Close LocalOutputStream
I/BtToSocketBase( 3775): Close localHostSocket
I/BtToSocketBase( 3775): Close bt in
,I/BtToSocketBase( 3775): Close bt out
I/BtToSocketBase( 3775): Close bt socket
I/BtToSocketBase( 3775): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3775): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3775): 2015-11-24T12:00:53.060Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2212): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2212): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: XT1039
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T12:00:56.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:56.916Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:56.917Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:56.917Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b244 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2212): onReceive
,I/BTConnectionReceiver( 1534): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1534): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 65
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:00:58.624Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:00:58.625Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:00:58.626Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3775): Found 7 peers.
I/SS      ( 3775): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3775): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3775): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Started service discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 3775): 2015-11-24T12:01:03.627Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:03.628Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:01:08.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:08.633Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:08.634Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:08.634Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 66
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:01:08.982Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:08.982Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:08.985Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:08.989Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- gotta redo : F8:95:C7:87:85:54, try count now: 2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:08.992Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:08.993Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:08.993Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 47515 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c96c rs_disc_pending=1,
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2212): process_service_search_attr_rsp,
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4bcf4 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5
,W/bt-btif ( 2212): invalid rfc slot id: 67
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:01:13.611Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:13.611Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:13.612Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2212): No record of the device:null
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:01:18.613Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:18.613Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:23.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:23.617Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:23.618Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:23.618Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a0,
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
W/bt-btif ( 2212): invalid rfc slot id: 68
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/jxcore-log( 3775): 2015-11-24T12:01:28.520Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/jxcore-log( 3775): 2015-11-24T12:01:28.520Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
I/jxcore-log( 3775): 2015-11-24T12:01:28.521Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:01:33.522Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:33.523Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:38.527Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:38.527Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:38.528Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:38.529Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE,
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 2212): PORT_StartCnf failed result:5
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5
W/bt-btif ( 2212): invalid rfc slot id: 69
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2212): No record of the device:null
,I/jxcore-log( 3775): 2015-11-24T12:01:42.519Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
I/jxcore-log( 3775): 2015-11-24T12:01:42.520Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/jxcore-log( 3775): 2015-11-24T12:01:42.521Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:01:47.524Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:47.524Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:01:52.527Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:52.528Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:52.529Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:52.529Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect,
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp,
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,V/KeepSync( 3684): Connecting to GoogleApiClient
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1831): Handling authorization failure
E/ClientConnectionOperation( 1831): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1831): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1831): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1831): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1831): 	,at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1831): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1831): 	... 7 more
,V/KeepSync( 3684): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3684): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a0
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
W/bt-btif ( 2212): invalid rfc slot id: 70
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
I/BluetoothBondStateMachine( 2212): No record of the device:null
,E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
,I/jxcore-log( 3775): 2015-11-24T12:01:57.524Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:57.524Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:01:57.524Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/KeepSync( 3684): IOException
,E/KeepSync( 3684): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3684): 	,at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3684): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3684): ,	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3684): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3684): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3684): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3684): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3684): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3684): ,	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3684): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140),
E/KeepSync( 3684): 	... 10 more
W/KeepSync( 3684): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 1019438, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3775): Cleared service requests,
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 7 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3775): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3775): 2015-11-24T12:02:02.525Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:02.526Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07,
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:02:07.529Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:07.530Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:07.531Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:07.531Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3775): Found 5 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(4): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5,
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c,
,W/bt-btif ( 2212): invalid rfc slot id: 71
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/jxcore-log( 3775): 2015-11-24T12:02:12.536Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:12.537Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:02:12.543Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:12.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 2
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:12.548Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:12.548Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:12.549Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null,
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77,
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 63545 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63),
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 72
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:02:13.900Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:13.901Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:13.901Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:02:18.903Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:18.903Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:23.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:23.908Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:23.909Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:23.910Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null,
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 73
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:02:25.431Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:25.432Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:25.433Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/jxcore-log( 3775): 2015-11-24T12:02:30.435Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:30.436Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3421, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3421, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3775): 2015-11-24T12:02:35.439Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:35.440Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:35.441Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:35.441Z SendDataConnector.js: do connect now
,I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 74
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:02:36.960Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:36.961Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:36.962Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:02:41.963Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:41.964Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:46.968Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:02:46.968Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T12:02:46.969Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:02:46.969Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3775): Starting to connect
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3775): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at blb.a(PG:3937)
E/HttpOperation( 3228): 	at czp.a(PG:18188)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 12 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 14 more
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3228): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3228): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3228): 	at jdm.a(PG:82)
E/HttpOperation( 3228): 	at jcs.o(PG:406)
E/HttpOperation( 3228): 	at jcn.a(PG:1379)
E/HttpOperation( 3228): 	at jcs.i(PG:143)
E/HttpOperation( 3228): 	at hec.a(PG:42)
E/HttpOperation( 3228): 	at hee.a(PG:102)
E/HttpOperation( 3228): 	at czr.a(PG:65)
E/HttpOperation( 3228): 	at kka.a(PG:108)
E/HttpOperation( 3228): 	at czp.a(PG:19176)
E/HttpOperation( 3228): 	at czp.a(PG:9081)
E/HttpOperation( 3228): 	at czq.run(PG:1686)
E/HttpOperation( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3228): 	at jdj.a(PG:4091)
E/HttpOperation( 3228): 	at jdj.a(PG:1125)
E/HttpOperation( 3228): 	at jdm.a(PG:77)
E/HttpOperation( 3228): 	... 15 more
E/HttpOperation( 3228): Caused by: faj: BadAuthentication
E/HttpOperation( 3228): 	at fal.a(PG:38)
E/HttpOperation( 3228): 	at jdj.a(PG:4089)
E/HttpOperation( 3228): 	... 17 more
,E/ExperimentLoader( 3228): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3228): 	at jdm.a(PG:82)
E/ExperimentLoader( 3228): ,	at jcs.o(PG:406)
E/ExperimentLoader( 3228): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3228): 	at jcs.i(PG:143)
E/ExperimentLoader( 3228): 	at hec.a(PG:42)
E/ExperimentLoader( 3228): 	at hee.a(PG:102)
E/ExperimentLoader( 3228): 	at czr.a(PG:65)
E/ExperimentLoader( 3228): 	at kka.a(PG:108)
E/ExperimentLoader( 3228): 	at czp.a(PG:19176),
E/ExperimentLoader( 3228): 	at czp.a(PG:9081)
E/ExperimentLoader( 3228): 	at czq.run(PG:1686)
E/ExperimentLoader( 3228): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3228): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3228): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3228): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 3228): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3228): 	at jdm.a(PG:77)
E/ExperimentLoader( 3228): 	... 15 more
E/ExperimentLoader( 3228): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3228): 	at fal.a(PG:38)
E/ExperimentLoader( 3228): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3228): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1082665, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 75
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:03:02.775Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:02.776Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:02.777Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3775): Added service request
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0,
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Started service discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3775): 2015-11-24T12:03:07.778Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:07.778Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:12.784Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:12.785Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:12.785Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:12.786Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 76
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:03:14.277Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:14.278Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:14.281Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:14.283Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 2
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:14.293Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:14.295Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:14.296Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 61730 ms, rnd: 5, ex: Connection to 90:E7:C4:F6:69:77 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c7a4 rs_disc_pending=1
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 77
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:03:15.201Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:15.201Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:15.202Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 7 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T12:03:20.203Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:20.204Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:25.208Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:25.209Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:25.209Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:25.210Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 78
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:03:26.022Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:26.023Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:26.023Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3775): 2015-11-24T12:03:31.025Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:31.025Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3775): Found 7 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T12:03:36.028Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:36.029Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:36.030Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:36.030Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 79
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:03:37.525Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:37.526Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:37.526Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:03:42.527Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:42.528Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:47.531Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:47.532Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:47.533Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:47.533Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 80
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:03:50.162Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:50.163Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:03:50.163Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3775): Started service discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3775): 2015-11-24T12:03:55.165Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:03:55.165Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3775): 2015-11-24T12:04:00.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:00.169Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:00.170Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:00.170Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BooksSync( 3714): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3714): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 48890(2MB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 2.259ms total 92.079ms
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3714): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3714): Soft error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3714): Sync error
E/BooksSync( 3714): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3714): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3714): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1122315, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 81
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:04:01.282Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:01.282Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:01.285Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:01.287Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 3
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:01.290Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:01.290Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:01.291Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null,
I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 46989 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 2205,
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 82
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:04:01.619Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:01.620Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:01.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0,
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3775): 2015-11-24T12:04:06.622Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:06.623Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T12:04:11.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:11.626Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:11.627Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:11.627Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 83
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:04:11.904Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:11.905Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:11.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3775): 2015-11-24T12:04:16.907Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:16.908Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68,
,I/jxcore-log( 3775): 2015-11-24T12:04:21.913Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:21.914Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:21.915Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:21.915Z SendDataConnector.js: do connect now,
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null,
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 84
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:04:23.375Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:23.376Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:23.377Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/art     ( 1504): Explicit concurrent mark sweep GC freed 66251(3MB) AllocSpace objects, 9(993KB) LOS objects, 36% free, 27MB/43MB, paused 1.400ms total 66.437ms
,V/GoogleAuthProtoRequest( 3856): [416] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [416] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3856): [416] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3775): 2015-11-24T12:04:28.378Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:28.379Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3775): Found 7 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/jxcore-log( 3775): 2015-11-24T12:04:33.383Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:33.384Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:33.384Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:33.385Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): ,
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 85
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:04:34.174Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:34.175Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:34.175Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:04:39.176Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:39.177Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:44.181Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:44.182Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:44.183Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:44.183Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 86
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:04:45.228Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:45.229Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:45.233Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:45.237Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : F8:95:C7:87:85:54, try count now: 3
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:45.240Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:04:45.240Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:04:45.241Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 43940 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c96c rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,E/bt-btif ( 2212): PORT_StartCnf failed result:5
W/bt-rfcomm( 2212): PORT_StartCnf failed result:5
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2212): invalid rfc slot id: 87
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
,I/jxcore-log( 3775): 2015-11-24T12:05:24.055Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/jxcore-log( 3775): 2015-11-24T12:05:24.057Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:24.058Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,I/jxcore-log( 3775): 2015-11-24T12:05:29.059Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:29.060Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/SS      ( 3775): We got empty peers list
I/SS      ( 3775): We got empty peers list
I/SS      ( 3775): We got empty peers list
,I/SS      ( 3775): We got empty peers list
,I/SS      ( 3775): We got empty peers list
,I/SS      ( 3775): We got empty peers list
,I/jxcore-log( 3775): 2015-11-24T12:05:34.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:34.065Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:34.066Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:05:34.066Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE,
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 1 peers.,
I/SS      ( 3775): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a0,
E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2212): invalid rfc slot id: 88
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
,E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:05:38.398Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:38.399Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/jxcore-log( 3775): 2015-11-24T12:05:38.399Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
,E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:05:43.400Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:43.401Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3775): Found 3 peers.
,I/SS      ( 3775): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3775): 2015-11-24T12:05:48.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:05:48.405Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:05:48.406Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:05:48.406Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): PORT_StartCnf failed result:5,
E/bt-btif ( 2212): PORT_StartCnf failed result:5
W/bt-btif ( 2212): invalid rfc slot id: 89,
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
,E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3775): 2015-11-24T12:05:53.659Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:53.660Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:05:53.661Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
,E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,V/GoogleAuthProtoRequest( 3856): [417] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1504): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1504): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1504): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1504): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1504): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3856): [417] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3856): [417] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3856): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3856): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3856): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3856): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3856): 	at com.a.a.k.run(SourceFile:110)
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3775): 2015-11-24T12:05:58.661Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:05:58.662Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:03.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:03.666Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:03.667Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:03.667Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): PORT_Star: remote_cod = 0x5a020c
,E/bt-btif ( 2212): PORT_Star: remote_cod = 0x5a020c
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
,E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
W/bt-btif ( 2212): invalid rfc slot id: 90
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/jxcore-log( 3775): 2015-11-24T12:06:08.701Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
,E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
I/jxcore-log( 3775): 2015-11-24T12:06:08.702Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:08.703Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3775): Found 6 peers.
I/SS      ( 3775): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3775): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT6558, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT6558, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3775): 2015-11-24T12:06:13.704Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:13.705Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:06:18.709Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:18.710Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:18.711Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE,
I/jxcore-log( 3775): ,
,I/jxcore-log( 3775): 2015-11-24T12:06:18.711Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): ,
I/        ( 3775): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2212): check_cod: remote_cod = 0x5a0
,E/bt-btif ( 2212): check_cod: remote_cod = 0x5a020c
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2212): invalid rfc slot id: 91
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2212): Device not in IRK list
E/bt-btif ( 2212): Do not find the bg connection mask for the remote device
I/jxcore-log( 3775): 2015-11-24T12:06:22.676Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:22.676Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3775): 
I/BluetoothBondStateMachine( 2212): No record of the device:null
I/BluetoothBondStateMachine( 2212): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 2212): In stable state, received invalid newState: 10
,I/jxcore-log( 3775): 2015-11-24T12:06:22.681Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3775): 
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
I/jxcore-log( 3775): 2015-11-24T12:06:22.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 3
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:22.688Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:22.689Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:22.689Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null,
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 97437 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 92
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:06:24.738Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:24.739Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:24.740Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
I/SS      ( 3775): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:06:29.741Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:29.742Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:34.745Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:34.746Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:34.747Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:34.747Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 93
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:06:37.689Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:37.690Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:37.690Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:06:42.692Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:42.693Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/        ( 3775): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT6558, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT6558, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3775): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3775): 2015-11-24T12:06:47.700Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:47.700Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:47.701Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77,
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T12:06:47.701Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 94
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3775): 2015-11-24T12:06:49.246Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:49.247Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:49.247Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T12:06:54.249Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:54.249Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3775): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3775): 2015-11-24T12:06:59.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:06:59.254Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:59.255Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:06:59.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null,
,I/BTConnectToThread( 3775): Starting to connect,
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 95
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:00.614Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:00.615Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:00.616Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/jxcore-log( 3775): 2015-11-24T12:07:05.618Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:05.619Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:10.623Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:10.624Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true,
I/jxcore-log( 3775): ,
I/jxcore-log( 3775): 2015-11-24T12:07:10.624Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:10.625Z SendDataConnector.js: do connect now,
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: 90:E7:C4:F6:69:77, name: null,
I/        ( 3775): Connecting to null, at 90:E7:C4:F6:69:77
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 96
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:13.433Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:13.434Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:13.437Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:13.440Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 3
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:13.443Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:13.443Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:13.444Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 50745 ms, rnd: 5, ex: Connection to 90:E7:C4:F6:69:77 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4c7a4 rs_disc_pending=1
,W/bt-btif ( 2212): bta_dm_check_av:0
W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 97
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:14.818Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:14.818Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:14.819Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2212): tBTM_SEC_DEV:0xa2f4b964 rs_disc_pending=0
W/bt-btif ( 2212): bta_dm_check_av:0
,W/bt-btif ( 2212): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3775): 2015-11-24T12:07:19.821Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:19.822Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:24.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:24.826Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:24.827Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:24.827Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null,
,I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 98
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3775): 2015-11-24T12:07:25.628Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:25.628Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:25.630Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:07:30.631Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:30.632Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/jxcore-log( 3775): 2015-11-24T12:07:35.636Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:35.637Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:35.637Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:35.638Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2212): invalid rfc slot id: 99
,I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:36.142Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:36.144Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:36.144Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T12:07:41.145Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:41.146Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3775): 2015-11-24T12:07:46.148Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:46.149Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:46.150Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:46.150Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect,
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 100
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:47.188Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:47.189Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:47.191Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:07:52.192Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:52.193Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3775): 2015-11-24T12:07:57.197Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:57.198Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:57.198Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:57.198Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3775): Starting to connect,
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at E0:DB:10:14:E2:C0,
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10,
D/        ( 2212): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 101
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:58.582Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:58.583Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:58.586Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:58.588Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ---- round done--------
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 4
I/jxcore-log( 3775): 
I/jxcore-log( 3775): do fake peer & start
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:58.590Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:58.591Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:58.592Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback round[0] time: 45140 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2212): info:x10,
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 102
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:07:59.436Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:07:59.436Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:07:59.437Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3775): Started service discovery
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3775): 2015-11-24T12:08:04.439Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:04.440Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:08:09.444Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:09.445Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:09.446Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:09.446Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3775): Starting to connect
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 103
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:08:09.863Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:09.864Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:09.865Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:08:14.866Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:14.866Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/jxcore-log( 3775): 2015-11-24T12:08:19.869Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:19.870Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:19.870Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:19.871Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null,
,I/BTConnectToThread( 3775): Starting to connect
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2212): invalid rfc slot id: 104
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:08:21.047Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed,
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:21.047Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:21.048Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3775): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:08:26.050Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:26.051Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3775): 2015-11-24T12:08:31.055Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:31.055Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:31.056Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:31.056Z SendDataConnector.js: do connect now
I/jxcore-log( 3775): 
,I/        ( 3775): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3775): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3775): Starting to connect
W/BluetoothAdapter( 3775): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2212): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [f8:95:c7:87:85:54]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2212): process_service_search_attr_rsp
,E/bt-btif ( 2212): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2212): invalid rfc slot id: 105
I/BTConnectToThread( 3775): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3775): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3775): 2015-11-24T12:08:32.139Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:32.140Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:32.140Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): timeout now
,I/jxcore-log( 3775): 
I/jxcore-log( 3775): dun
I/jxcore-log( 3775): 
I/jxcore-log( 3775): weAreDoneNow , resultArray.length: 12
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): done, now sending data to server
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): -- RESULT DATA {"name:":"motorola-Nexus 6_PT5587","time":1000121,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":27309,"result":"OK","connections":2,"tryCount":1},{"name":"00:F4:6F:30:E0:6C","time":19976,"result":"OK","connections":2,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":35979,"result":"OK","connections":2,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":6202,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":5028,"result":"OK","connections":1,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":19267,"result":"OK","connections":2,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":18624,"result":"OK","connections":2,"tryCount":1},{"name":"7C:F9:0E:37:96:AB","time":1855,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":1926,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:11:AE:67","time":4200,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":9397,"result":"OK","connections":1,"tryCount":1
,I/jxcore-log( 3775): sendList : 100% : 35979 ms, 99% : 35979 ms, 95 : 27309 ms, 90% : 27309 ms.,
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Result count 12, range 1855 ms to  35979 ms.
I/jxcore-log( 3775): 
I/jxcore-log( 3775): sendList failed peers count : 4 [25 %]
I/jxcore-log( 3775): 
I/jxcore-log( 3775): - Peer ID : F8:95:C7:87:85:54, Tried : 4
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
I/jxcore-log( 3775): 
I/jxcore-log( 3775): - Peer ID : 90:E7:C4:F6:69:77, Tried : 3
I/jxcore-log( 3775): 
I/jxcore-log( 3775): - Peer ID : E0:DB:10:14:E2:C0, Tried : 4
I/jxcore-log( 3775): 
I/jxcore-log( 3775): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:08:33.226Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:33.226Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3775): 
I/jxcore-log( 3775): 2015-11-24T12:08:33.227Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3775): 
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-btif ( 2212): info:x10
D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, f, 410d
E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 7 peers.,
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 8 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8,
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42,
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0,
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 6 peers.,
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,W/bt-btif ( 2212): info:x10
,D/        ( 2212): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2212): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3775): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(5): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2212): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2212): aclStateChangeCallback: Device is NULL
,I/        ( 3775): Started service discovery
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 3775): Found 3 peers.
,I/SS      ( 3775): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3775): Peer(3): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Cleared service requests,
I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Cleared service requests
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3775): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51,
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Cleared service requests
I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 5 peers.
,I/SS      ( 3775): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3775): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50,
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:,
I/        ( 3775): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT9877, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT9877, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86,
,I/        ( 3775): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/HeadsetStateMachine( 2212): Disconnected process message: 10, size: 0
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 4 peers.,
I/SS      ( 3775): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3775): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3775): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3775): Added service request
,I/        ( 3775): Started service discovery,
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3775): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3775): Found 4 peers.
,I/SS      ( 3775): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3775): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3775): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3775): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3775): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3775): Added service request
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1249): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3775): Started service discovery
,I/wpa_supplicant( 1249): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3775): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3775): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3775): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3775): Cleared service requests
,I/        ( 3775): Started peer discovery
,I/jxcore-log( 3775): DBG, CoordinatorConnector command called
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3775): 
I/jxcore-log( 3775): stop tests now !
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): stop current!
I/jxcore-log( 3775): 
I/jxcore-log( 3775): testSendData stopped
I/jxcore-log( 3775): 
I/        ( 3775): Stoping All
I/        ( 3775): Stopping services
I/        ( 3775): Stopping services
,I/        ( 3775): Stop Bluetooth
I/        ( 3775): Stop Bluetooth
I/BTListenerThread( 3775): Stopped
,I/jxcore-log( 3775): StopBroadcasting went ok
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): 2015-11-24T12:12:53.207Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3775): 
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1249): P2P-FIND-STOPPED 
I/        ( 3775): Cleared local services
I/        ( 3775): Cleared service requests
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1249): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 3775): DBG, CoordinatorConnector command called
I/jxcore-log( 3775): 
I/jxcore-log( 3775): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"7C:F9:0E:37:96:AB\",\"time\":1855,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":1926,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:11:AE:67\",\"time\":4200,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:3C:51\",\"time\":5028,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":6202,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"08:EC:A9:50:76:27\",\"time\":7918,\"result\":\"OK\",\"connections\":1,\"tryCount\":2},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":9397,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":18624,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":19267,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":19
,I/jxcore-log( 3775): ****TEST TOOK:  ms ****
I/jxcore-log( 3775): 
I/jxcore-log( 3775): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3775): 
I/jxcore-log( 3775): stop tests now !
I/jxcore-log( 3775): 
,I/jxcore-log( 3775): end, event received
I/jxcore-log( 3775): 
I/jxcore-log( 3775): CoordinatorConnector close called
I/jxcore-log( 3775): 
I/jxcore-log( 3775): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3775): 
I/jxcore-log( 3775): The Coordinator has disconnected!
I/jxcore-log( 3775): 
I/jxcore-log( 3775): The Coordinator has closed!
I/jxcore-log( 3775): 
I/jxcore-log( 3775): stop tests now !
I/jxcore-log( 3775): 
I/jxcore-log( 3775): turning Radios off
I/jxcore-log( 3775): 
I/jxcore-log( 3775): Toggling radios to false
I/jxcore-log( 3775): 
D/BluetoothAdapter( 3775): enable(): BT is already enabled..!
I/        ( 3775): Stopped peer discovery
I/chromium( 3775): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime( 4444): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4444): CheckJNI is OFF,
,D/AndroidRuntime( 4444): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  823): Killing 3775:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  823): Skipping PackageSetting{2b648c2 com.example.hello/10272} due to missing metadata
,I/WindowState(  823): WIN DEATH: Window{3320b290 u0 com.test.thalitest/com.test.thalitest.MainActivity},
,E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3775,
,W/ActivityManager(  823): Force removing ActivityRecord{22a34471 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state,
D/WifiService(  823): Client connection lost with reason: 4
,V/ActivityManager(  823): Display changed displayId=0
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  823): Spurious death for ProcessRecord{11d9f1f6 3775:com.test.thalitest/u0a265}, curProc for 3775: null
,D/TaskPersister(  823): removeObsoleteFile: deleting file=24_task.xml
,I/Keyboard.Facilitator( 1222): resetDictionaries() : en_US
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
,D/BuaReceiver( 3570): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 85251(3MB) AllocSpace objects, 20(320KB) LOS objects, 22% free, 27MB/35MB, paused 347us total 48.572ms
I/Keyboard.Facilitator.DecoderInitializer( 1222): run()
,I/Decoder ( 1222): createOrResetDecoder
,I/art     ( 1074): Explicit concurrent mark sweep GC freed 75444(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 1.172ms total 60.684ms,
,D/VoicemailCleanupService( 1391): Cleaning up data for package: com.test.thalitest
,I/art     (  823): Explicit concurrent mark sweep GC freed 64422(3MB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 1.860ms total 82.982ms
,I/ActivityManager(  823): Start proc 4462:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ConfigService( 1504): onCreate
,W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3775 uid 10265
,I/art     (  823): WaitForGcToComplete blocked for 62.214ms for cause Explicit
,I/Keyboard.Facilitator( 1222): onFinishInput()
,W/LocationOracleImpl( 1534): Best location was null
,I/art     ( 1320): Explicit concurrent mark sweep GC freed 5057(369KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 1.319ms total 25.114ms
,I/HotwordRecognitionRnr( 1534): Starting hotword detection.
I/MicrophoneInputStream( 1534): mic_starting com.google.android.apps.gsa.speech.audio.u@1d19d558
,I/AudioFlinger(  359): AudioFlinger's thread 0xb40ed000 ready to run
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): run()
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1534): mic_started com.google.android.apps.gsa.speech.audio.u@1d19d558
,D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,W/ContextImpl( 4462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,E/NetworkScheduler.SchedulerReceiver( 1504): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1504): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/LocationOracleImpl( 1534): Best location was null
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1222): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1222): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1222): run()
I/StatsUtilsManager( 1222): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1222): shouldRecordStats() = Too Soon
,W/LocationOracleImpl( 1534): Best location was null
,D/PackageBroadcastService( 1831): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1831): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1831): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1831): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1831): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1831): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1831): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1534): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1320): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2fe45ef9 new=com.google.android.velvet.VelvetApplication@2fe45ef9
,I/HotwordWorker( 1534): onReady
,D/GOOGLEHELP_CompatibleDatabase( 1831): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1831): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1831): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1831): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1831): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1831): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1831): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ConfigFetchService( 1831): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 1831): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1831): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a5671e4}
,D/GOOGLEHELP_CompatibleDatabase( 1831): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1831): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1831): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
I/ConfigFetchService( 1831): service connected
D/GOOGLEHELP_CompatibleDatabase( 1831): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1831): CP2 sync disabled
,I/Icing   ( 1831): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 1831): Using Auth Proxy for data requests.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=25.00 rxSuccessRate=31.00 targetRoamBSSID=any RSSI=-44
,W/BaseAppContext( 1831): Using Auth Proxy for data requests.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=100.50 rxSuccessRate=333.00 targetRoamBSSID=any RSSI=-44
,I/art     (  823): Explicit concurrent mark sweep GC freed 12969(624KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 3.838ms total 226.829ms
,I/UpdateIcingCorporaServi( 1534): UpdateCorporaTask done [took 76 ms] updated apps [took 75 ms] 
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660781843
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  823): Start proc 4513:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,D/Launcher.Workspace( 1320): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1320): 11683562 - stripEmptyScreens()
,I/art     ( 4444): System.exit called, status: 0
I/AndroidRuntime( 4444): VM exiting with result code 0.
,I/kickstart(  877): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_lock
,I/ActivityManager(  823): Start proc 4532:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  823): Killing 3382:com.android.providers.calendar/u0a3 (adj 15): empty #17
,E/kickstart(  877): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  877): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/ExternalStorage( 4532): After updating volumes, found 1 active roots
,W/ResourcesManager( 3638): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3638): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,D/Documents( 4513): Update found 7 roots in 386ms
,D/Documents( 4513): Update found 7 roots in 240ms
,E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/Icing   ( 1831): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/Icing   ( 1831): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 1831): Could not init tag ds.tag.deleted
,I/Icing   ( 1831): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a5671e4}
,I/art     ( 1860): Explicit concurrent mark sweep GC freed 20348(1181KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 2.050ms total 67ms
,E/DataBuffer( 1860): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@737d21b)
,W/FileUtils( 1534): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 1534): Failed to write new file: loracle.new
W/LocationOracleImpl( 1534): Best location was null
,E/LocationReceiver( 1534): Received bad location: null
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/Search.SharedPreferencesProto( 1534): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1504): onDestroy
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
E/kickstart(  877): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  877): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,E/QMI_FW  (  823): xport_send: Sendto failed for port 3840,
E/LocSvc_api_v02(  823): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
E/QMI_FW  (  823): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  823): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_ApiV02(  823): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
