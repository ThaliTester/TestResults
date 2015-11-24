#### Test 5133502860beea6_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3635): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3635): CheckJNI is OFF
D/AndroidRuntime( 3635): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{1eeec76e token=Token{43c4ee9 ActivityRecord{2913ab70 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3635): Shutting down VM
V/WindowManager(  822): Adding window Window{3ad50c2b u0 Starting com.test.thalitest} at 3 of 8 (after Window{19305a62 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1543): mic_close com.google.android.apps.gsa.speech.audio.u@43d2400
I/HotwordDetector( 1543): Closing mic
I/ActivityManager(  822): Start proc 3650:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1543): Stopping hotword detection.
I/HotwordRecognitionRnr( 1543): Hotword detection finished
I/ActivityManager(  822): Killing 3104:com.google.android.gm/u0a78 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703081235
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  822): Killing 2727:com.google.android.apps.maps/u0a65 (adj 15): empty #18
I/kickstart(  877): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  877): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  877): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/WebViewFactory( 3650): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3650): Time to load native libraries: 5 ms (timestamps 8237-8242)
I/LibraryLoader( 3650): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3650): Binding Chromium to main looper Looper (main, tid 1) {3941af9b}
I/LibraryLoader( 3650): Expected native library version number "",actual native library version number ""
I/chromium( 3650): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3650): Initializing chromium process, singleProcess=true
W/art     ( 3650): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3650): ApplicationContext is null in ApplicationStatus
W/chromium( 3650): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3650): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3650): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3650): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dd5561b:true
W/art     ( 3650): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3650): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3650): CordovaWebView is running on device made by: motorola
W/art     ( 3650): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3650): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3650): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3650): Validating map...
V/WindowManager(  822): Adding window Window{3733fc0b u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{3ad50c2b u0 Starting com.test.thalitest})
W/chromium( 3650): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3650): Initialized EGL, version 1.4
D/OpenGLRenderer( 3650): Enabling debug mode 0
I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +932ms (total +1m35s467ms)
I/Keyboard.Facilitator( 1248): onFinishInput()
W/BindingManager( 3650): Cannot call determinedVisibility() - never saw a connection for the pid: 3650
,D/JsMessageQueue( 3650): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3650): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1574413312
,D/JX-Cordova( 3650): jxcore cordova android initializing
,I/kickstart(  877): STATUS: Received file 'm9kefs2'
I/kickstart(  877): STATUS: 950272 bytes transferred in 0.990612 seconds
I/kickstart(  877): STATUS: Successfully downloaded files from target 
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  877): STATUS: Sahara protocol completed
,W/jxcore-log( 3650): Initializing JXcore engine
W/jxcore-log( 3650): JXcore engine is ready
,W/jxcore-log( 3650): Starting JXcore engine
,W/.test.thalitest( 3650): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11847]" dev="sockfs" ino=11847 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3650): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3650): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10541]" dev="sockfs" ino=10541 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3650): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22224]" dev="sockfs" ino=22224 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3650): Platform android
,W/jxcore-log( 3650): 
W/jxcore-log( 3650): Process ARCH arm
W/jxcore-log( 3650): 
,I/jxcore-log( 3650): JXcore Cordova bridge is ready!
I/jxcore-log( 3650): 
W/jxcore-log( 3650): JXcore engine is started
,I/Choreographer( 3650): Skipped 127 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3650): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3650): Toggling radios to true
I/jxcore-log( 3650): 
,D/BluetoothAdapter( 3650): enable(): BT is already enabled..!
,I/art     ( 1543): WaitForGcToComplete blocked for 93.847ms for cause HomogeneousSpaceCompact
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3650): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3650): 
I/jxcore-log( 3650): my name is : motorola-Nexus 6_PT1620
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): attempting to connect to test coordinator
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): check test folder
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): found test : ./testFindPeers.js
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): found test : ./testReConnect.js
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): found test : ./testSendData.js
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Test app app.js loaded
I/jxcore-log( 3650): 
,I/Choreographer( 3650): Skipped 115 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 3650): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3650): 
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3039): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3039): [1] 5.onFinished: Scheduling replication attempt 2.
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): BLE supported!!
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.75 rxSuccessRate=2.46 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3039): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3039): [1] 5.onFinished: Scheduling replication attempt 3.
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.89 rxSuccessRate=2.61 targetRoamBSSID=any RSSI=-44
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (321 us)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  822): Display changed displayId=0
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0,
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 11
,E/native  (  822): do suspend false
,I/Keyboard.Facilitator( 1248): onFinishInput()
,E/WifiStateMachine(  822): cancelDelayedScan -> 13,
,E/native  (  822): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,I/art     (  822): Explicit concurrent mark sweep GC freed 41376(2MB) AllocSpace objects, 13(302KB) LOS objects, 32% free, 33MB/49MB, paused 2.729ms total 112.981ms
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44,
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3650): 
,V/KeepSync( 3556): Connecting to GoogleApiClient
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1819): Handling authorization failure
,E/ClientConnectionOperation( 1819): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1819): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1819): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
,E/ClientConnectionOperation( 1819): ,	at com.google.android.gms.drive.api.a.l.a(SourceFile:62),
E/ClientConnectionOperation( 1819): ,	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1819): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1819): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ClientConnectionOperation( 1819): 	,at java.lang.Thread.run(Thread.java:818)
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
,V/KeepSync( 3556): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3556): IOException
E/KeepSync( 3556): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3556): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3556): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3556): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3556): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3556): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3556): 	... 10 more
W/KeepSync( 3556): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 169804, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Start proc 3731:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/art     (  368): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 1.422ms total 20.085ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 6(192B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 225us total 16.977ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 241us total 11.143ms
,I/VacuumService( 1428): Vacuum at: now=1448361457263 tag=VacuumService
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1428): Explicit concurrent mark sweep GC freed 36611(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.547ms total 36.112ms
,I/GoogleURLConnFactory( 1428): Using platform SSLCertificateSocketFactory
,V/GoogleAuthProtoRequest( 3731): [395] a.<init>: mAccountName set to: thalitester@gmail.com
,W/Uploader( 1428): No account for auth token provided
,D/Finsky  ( 3039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3039): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3039): [1] 5.onFinished: Scheduling replication attempt 4.
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [395] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [395] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3731): [396] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [396] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3731): [396] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,W/Uploader( 1428): No account for auth token provided
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1428): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1428): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1428): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1428): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1428): No account for auth token provided
,W/Uploader( 1428): No account for auth token provided
,W/Uploader( 1428): No account for auth token provided
,W/Uploader( 1428): No account for auth token provided
,W/Uploader( 1428): No account for auth token provided
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1428): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1428): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1428): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78),
E/Uploader( 1428): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1428): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1428): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1428): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1428): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1428): No account for auth token provided
,W/Uploader( 1428): No account for auth token provided
,W/Uploader( 1428):  no longer exists, so no auth token.
,W/Uploader( 1428): No account for auth token provided
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1428): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1428): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1428): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1428): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1428): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1428): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1428): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1428): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1428): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1428): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,I/ActivityManager(  822): Killing 2303:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  822): Explicit concurrent mark sweep GC freed 32816(1472KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.580ms total 83.317ms,
,D/Finsky  ( 3039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3039): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3039): [1] 5.onFinished: Scheduling replication attempt 5.,
,I/BooksSync( 3587): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3587): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at blb.a(PG:3937)
E/HttpOperation( 3351): 	at czp.a(PG:18188)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 12 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 14 more
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at hec.a(PG:42)
E/HttpOperation( 3351): 	at hee.a(PG:102)
E/HttpOperation( 3351): 	at czr.a(PG:65)
E/HttpOperation( 3351): 	at kka.a(PG:108)
E/HttpOperation( 3351): 	at czp.a(PG:19176)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 15 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 17 more
,E/ExperimentLoader( 3351): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): 	at jdm.a(PG:82)
E/ExperimentLoader( 3351): 	at jcs.o(PG:406)
E/ExperimentLoader( 3351): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3351): 	at jcs.i(PG:143)
E/ExperimentLoader( 3351): 	at hec.a(PG:42)
E/ExperimentLoader( 3351): 	at hee.a(PG:102)
E/ExperimentLoader( 3351): 	at czr.a(PG:65)
E/ExperimentLoader( 3351): 	at kka.a(PG:108)
E/ExperimentLoader( 3351): 	at czp.a(PG:19176)
E/ExperimentLoader( 3351): 	at czp.a(PG:9081)
E/ExperimentLoader( 3351): 	at czq.run(PG:1686)
E/ExperimentLoader( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3351): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3351): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3351): 	at jdm.a(PG:77)
E/ExperimentLoader( 3351): 	... 15 more
E/ExperimentLoader( 3351): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3351): 	at fal.a(PG:38)
E/ExperimentLoader( 3351): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3351): 	... 17 more
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3587): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3587): Soft error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3587): Sync error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3587): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 170375, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 170869, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,V/GoogleAuthProtoRequest( 3731): [397] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [397] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3731): [397] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3039): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3039): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3039): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1248): run()
,I/Keyboard.Facilitator( 1248): flushDynamicLanguageModels()
,I/ConfigService( 1428): onCreate
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/ConfigService( 1428): onDestroy
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3650): 
,V/KeepSync( 3556): Connecting to GoogleApiClient
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3556): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3556): IOException
E/KeepSync( 3556): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3556): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3556): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3556): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3556): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3556): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3556): 	... 10 more
W/KeepSync( 3556): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 295259, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3650): DBG, CoordinatorConnector connect called
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Coordinator is now connected to the server!
I/jxcore-log( 3650): 
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3731): [398] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1428): Explicit concurrent mark sweep GC freed 63973(3MB) AllocSpace objects, 7(689KB) LOS objects, 36% free, 27MB/43MB, paused 1.991ms total 46.347ms
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [398] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [398] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3587): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3587): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3587): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3587): Soft error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3587): Sync error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3587): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 324720, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  822): Explicit concurrent mark sweep GC freed 32557(1412KB) AllocSpace objects, 11(741KB) LOS objects, 31% free, 34MB/50MB, paused 2.372ms total 94.677ms
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3b68a89}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3b68a89}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1428): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1428): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1428): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1428): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1428): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1428): ,	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1428): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3039): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3039): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3039): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3039): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3039): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3039): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3039): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3039): Ignoring header User-Agent because its value was null.
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3351): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at blb.a(PG:3937)
E/HttpOperation( 3351): 	at czp.a(PG:18188)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 12 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 14 more
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at hec.a(PG:42)
E/HttpOperation( 3351): 	at hee.a(PG:102)
E/HttpOperation( 3351): 	at czr.a(PG:65)
E/HttpOperation( 3351): 	at kka.a(PG:108)
E/HttpOperation( 3351): 	at czp.a(PG:19176)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 15 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 17 more
E/ExperimentLoader( 3351): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): 	at jdm.a(PG:82)
E/ExperimentLoader( 3351): 	at jcs.o(PG:406)
E/ExperimentLoader( 3351): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3351): 	at jcs.i(PG:143)
E/ExperimentLoader( 3351): 	at hec.a(PG:42)
E/ExperimentLoader( 3351): 	at hee.a(PG:102)
E/ExperimentLoader( 3351): 	at czr.a(PG:65)
E/ExperimentLoader( 3351): 	at kka.a(PG:108)
E/ExperimentLoader( 3351): 	at czp.a(PG:19176)
E/ExperimentLoader( 3351): 	at czp.a(PG:9081)
E/ExperimentLoader( 3351): 	at czq.run(PG:1686)
E/ExperimentLoader( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3351): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3351): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3351): 	at jdm.a(PG:77)
E/ExperimentLoader( 3351): 	... 15 more
E/ExperimentLoader( 3351): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3351): 	at fal.a(PG:38)
E/ExperimentLoader( 3351): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3351): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 327604, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector command called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":16,"addressList":[{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Start now : testSendData.js
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): stop tests now !
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 16
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): check server
I/jxcore-log( 3650): 
I/jxcore-log( 3650): serverPort is 57332
I/jxcore-log( 3650): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3650): Stoping All
I/        ( 3650): Stopping services
I/        ( 3650): Stop Bluetooth
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3650): Start-My BT: F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3650):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}
,D/WifiService(  822): New client listening to asynchronous messages
,I/        ( 3650): All stuff available and enabled
I/        ( 3650): Stoping All
I/        ( 3650): Stopping services
,I/        ( 3650): Stop Bluetooth
I/        ( 3650): Starting All
I/        ( 3650): Stopping services
I/        ( 3650): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2174ae6d
I/        ( 3650): Stopping services
,I/        ( 3650): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3650): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, length : 82,
,I/        ( 3650): peerDiscoveryTimer timeout value:9686
,I/        ( 3650): Stop Bluetooth
,I/        ( 3650): StartBluetooth listener
I/        ( 3650): StartBluetooth listener
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3650): StartBroadcasting started ok
I/jxcore-log( 3650): 
,I/BTListenerThread( 3650): starting to listen
I/BTListenerThread( 3650): waiting to accept incoming Connection
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:34.933Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:34.935Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:34.935Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at E0:DB:10:1F:C9:5E
,I/jxcore-log( 3650): 2015-11-24T10:41:34.948Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3650): 
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 3650): We already were running, thus doing nothing
I/        ( 3650): Added local service
I/        ( 3650): Cleared service requests
,I/        ( 3650): Stopped peer discovery
,I/        ( 3650): Started peer discovery
I/        ( 3650): Discovery state changed to Started.
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): No ag scb for peer addr
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config( 2394): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
D/BluetoothAdapterProperties( 2394): Failed to remove device: E0:DB:10:1F:C9:5E
,I/ActivityManager(  822): Start proc 3841:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f7110aa:true
,I/ActivityManager(  822): Killing 2964:com.google.android.talk/u0a61 (adj 15): empty #17
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 1 peers.
I/SS      ( 3650): Peer(1): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2394): L2CAP - no CCB for conn rsp, LCID: 66 RCID: 68
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3650): we got incoming connection
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3650): Starting to Handshake
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread,
W/bt-btif ( 2394): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started,
,I/BTListenerThread( 3650): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3650): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT6575
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, samsung-SM-N9005_PT6575
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332,
,I/BTConnectToThread( 3650): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/BTConnectToThread( 3650): HandshakeOk : samsung-SM-N9005_PT6575
I/HS      ( 3650): Hand Shake finished outgoing for : samsung-SM-N9005_PT6575
,I/jxcore-log( 3650): 2015-11-24T10:41:43.149Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, samsung-SM-N9005_PT6575
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): mHTTPPort  set to : 41482
,I/BtConnectorHelper( 3650): Request socket is using : 41482
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :41482
,I/jxcore-log( 3650): 2015-11-24T10:41:43.468Z SendDataConnector.js: CLIENT connected to 41482, error: null
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.469Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 41482
,I/BtToRequestSocket( 3650): Set local streams
I/BtToRequestSocket( 3650): rin ended ---------------------------;
I/jxcore-log( 3650): 2015-11-24T10:41:43.480Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1393
,I/jxcore-log( 3650): 2015-11-24T10:41:43.700Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.706Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.717Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.722Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.732Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.744Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.752Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.773Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.787Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.844Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.892Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.953Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:43.959Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.027Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.069Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.098Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.124Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.131Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:41:44.184Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.191Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.229Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.233Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.237Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.288Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.297Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.321Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.335Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.336Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.346Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.347Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
I/BtConnectorHelper( 3650): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3650): 2015-11-24T10:41:44.359Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:41:44.364Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:41:44.365Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:41:44.365Z SendDataConnector.js: do connect now,
,I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3650): Connecting to null, at E0:DB:10:14:E2:C0
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 9404 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3650): 2015-11-24T10:41:44.380Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.401Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.404Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa5eb4 rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3650): 2015-11-24T10:41:44.618Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): 2015-11-24T10:41:44.620Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.625Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.630Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.659Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:41:44.665Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.700Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.703Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.710Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.748Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.929Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:44.995Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.298Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.303Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.369Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.543Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.582Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.619Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.630Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.664Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:45.743Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa5eb4 rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): invalid rfc slot id: 4
I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT6575
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream,
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Close bt in
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3650): Close bt out
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT6575
I/BtToSocketBase( 3650): Close bt socket,
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out,
I/BtToSocketBase( 3650): Close bt socket
D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
I/jxcore-log( 3650): 2015-11-24T10:41:46.070Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cd63038:true
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2394): PORT_StartCnf failed result:5
E/bt-btif ( 2394): PORT_StartCnf failed result:5
E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothBondStateMachine( 2394): No record of the device:null
W/bt-btif ( 2394): invalid rfc slot id: 7
E/bt-btm  ( 2394): Device not in IRK list
E/bt-btif ( 2394): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 9 Address: E0:DB:10:14:E2:C0 newState: 0
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothBondStateMachine( 2394): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:41:56.637Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:41:56.637Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:41:56.638Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,V/GoogleAuthProtoRequest( 3731): [399] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [399] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [399] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): ,	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3650): 2015-11-24T10:42:01.639Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:01.640Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:06.644Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:06.645Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:06.646Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:06.647Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2394): invalid rfc slot id: 8
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:42:28.878Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:28.879Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:28.880Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:33.881Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:33.882Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 4 peers.
,I/SS      ( 3650): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(2): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3650): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(4): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3650): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/jxcore-log( 3650): 2015-11-24T10:42:38.887Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:38.888Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:38.889Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:38.889Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): ,
,I/        ( 3650): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/        ( 3650): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6835, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6835, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3650): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT4125, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT4125, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86,
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config( 2394): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: E0:DB:10:14:E2:C0
I/BluetoothBondStateMachine( 2394): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/BTConnectToThread( 3650): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5955","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : samsung-SM-N910C_PT5955
I/HS      ( 3650): Hand Shake finished outgoing for : samsung-SM-N910C_PT5955
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, samsung-SM-N910C_PT5955
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): mHTTPPort  set to : 38569
,I/BtConnectorHelper( 3650): Request socket is using : 38569
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :38569
,I/jxcore-log( 3650): 2015-11-24T10:42:46.670Z SendDataConnector.js: CLIENT connected to 38569, error: null
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:46.671Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 38569
I/BtToRequestSocket( 3650): Set local streams
,I/jxcore-log( 3650): 2015-11-24T10:42:46.680Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
I/BtToRequestSocket( 3650): rin ended ---------------------------;
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:675
,I/jxcore-log( 3650): 2015-11-24T10:42:47.068Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:47.145Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:47.152Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:47.239Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:47.244Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:47.650Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:47.929Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:48.270Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:48.623Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:49.090Z SendDataConnector.js: CLIENT is data received : 100000
,I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:49.091Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:49.096Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): 2015-11-24T10:42:49.098Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
I/BtConnectorHelper( 3650): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed,
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out,
,I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3650): 2015-11-24T10:42:49.109Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
,I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:49.112Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
,I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:49.113Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:42:49.113Z SendDataConnector.js: do connect now,
I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: F8:95:C7:87:85:54, name: null
I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 64727 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa607c rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa607c rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6244 rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3650): Found 3 peers.
,I/SS      ( 3650): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(3): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
W/bt-rfcomm( 2394): check_cod: remote_cod = 0x5a0
,W/bt-btif ( 2394): invalid rfc slot id: 10
I/BluetoothBondStateMachine( 2394): No record of the device:null
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:85:54 newState: 0
E/BluetoothBondStateMachine( 2394): In stable state, received invalid newState: 10
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:42:59.361Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:59.362Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:42:59.363Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
E/bt-btm  ( 2394): Device not in IRK list
E/bt-btif ( 2394): Do not find the bg connection mask for the remote device
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3650): 2015-11-24T10:43:04.364Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:04.365Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3650): Found 4 peers.
I/SS      ( 3650): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3650): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/jxcore-log( 3650): 2015-11-24T10:43:09.369Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:09.370Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:09.371Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:09.371Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): ,
,I/        ( 3650): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3650): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10,
D/        ( 2394): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,I/        ( 3650): Started service discovery,
,D/btif_config( 2394): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2394): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
,I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTConnectToThread( 3650): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1372","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : LGE-LG-D722_PT1372
I/HS      ( 3650): Hand Shake finished outgoing for : LGE-LG-D722_PT1372
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, LGE-LG-D722_PT1372
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtToRequestSocket( 3650): mHTTPPort  set to : 48245
I/BtConnectorHelper( 3650): Request socket is using : 48245,
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :48245
,I/jxcore-log( 3650): 2015-11-24T10:43:11.824Z SendDataConnector.js: CLIENT connected to 48245, error: null
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:11.825Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 48245
,I/BtToRequestSocket( 3650): Set local streams
I/jxcore-log( 3650): 2015-11-24T10:43:11.833Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): rin ended ---------------------------;
,I/jxcore-log( 3650): 2015-11-24T10:43:12.029Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3650): 2015-11-24T10:43:12.257Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:12.421Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:12.479Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:12.603Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:12.709Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:12.776Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:12.910Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:13.037Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:13.138Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:13.139Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:13.145Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:13.147Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
,I/BtConnectorHelper( 3650): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,I/BtToRequestSocket( 3650): Close server socket
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3650): 2015-11-24T10:43:13.154Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:13.160Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:13.161Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:13.161Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3650): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3650): Starting to connect,
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 24027 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6244 rs_disc_pending=1,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6244 rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND,
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1543): Bluetooth Device Name: G3s-1
,I/        ( 3650): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6835, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6835, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: G3s-1,
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6244 rs_disc_pending=0
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,D/btif_config( 2394): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1,
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State,
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2394): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1372","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1372","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1372, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1372, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3650): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1372","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
I/HS      ( 3650): Incoming connection Hand Shake finished for : LGE-LG-D722_PT1372
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, LGE-LG-D722_PT1372
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:43:20.213Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.608Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.612Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.620Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.624Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.628Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.662Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.707Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.739Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.745Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.752Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.758Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.789Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.829Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.833Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.841Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.878Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.911Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.914Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.918Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.925Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:20.968Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.008Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.038Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.042Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.050Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.088Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.095Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.128Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.138Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.144Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.209Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.215Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.219Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.225Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.230Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.268Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.274Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.277Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:21.311Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 6
,I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1372
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
,I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close bt in
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT1372
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,I/jxcore-log( 3650): 2015-11-24T10:43:21.357Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x4f
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2394): info:x10,
D/        ( 2394): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa640c rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config( 2394): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
I/BTConnectToThread( 3650): Starting to Handshake
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTConnectToThread( 3650): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : HTC-HTC One_M8_PT5312
I/HS      ( 3650): Hand Shake finished outgoing for : HTC-HTC One_M8_PT5312
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, HTC-HTC One_M8_PT5312
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3650): mHTTPPort  set to : 53042
I/BtConnectorHelper( 3650): Request socket is using : 53042
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :53042
,I/jxcore-log( 3650): 2015-11-24T10:43:29.598Z SendDataConnector.js: CLIENT connected to 53042, error: null
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:29.599Z SendDataConnector.js: CLIENT starting client 
,I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 53042
,I/BtToRequestSocket( 3650): Set local streams
I/BtToRequestSocket( 3650): rin ended ---------------------------;
I/jxcore-log( 3650): 2015-11-24T10:43:29.608Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:408
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3650): 2015-11-24T10:43:29.749Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:29.758Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11119
,I/jxcore-log( 3650): 2015-11-24T10:43:29.797Z SendDataConnector.js: CLIENT is data received : 30000,
,I/jxcore-log( 3650): 
I/        ( 3650): Cleared service requests
I/        ( 3650): Started peer discovery,
,I/jxcore-log( 3650): 2015-11-24T10:43:29.812Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3650): 2015-11-24T10:43:30.128Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 5 peers.
,I/SS      ( 3650): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3650): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/jxcore-log( 3650): 2015-11-24T10:43:30.264Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.350Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.371Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.427Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.465Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.466Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:30.470Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:30.471Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
I/BtConnectorHelper( 3650): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
,I/jxcore-log( 3650): 2015-11-24T10:43:30.482Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.486Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:30.487Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:30.487Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at 90:E7:C4:F6:69:77
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 17306 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3650): Started service discovery
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa640c rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: HTC One_M8
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x40,
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 14
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:43:36.700Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:36.701Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:36.701Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6835, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6835, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): 2015-11-24T10:43:41.703Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:41.704Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,V/KeepSync( 3556): Connecting to GoogleApiClient
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1819): Handling authorization failure,
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
E/ClientConnectionOperation( 1819): 	,... 7 more
,V/KeepSync( 3556): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3556): IOException
E/KeepSync( 3556): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3556): 	,at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3556): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3556): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
,E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3556): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3556): ,	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3556): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3556): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3556): 	,... 10 more
W/KeepSync( 3556): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 545662, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): 2015-11-24T10:43:46.706Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:46.706Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:46.707Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:46.707Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3650): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 15
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:43:51.852Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:51.853Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:43:51.854Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3650): Found 6 peers.
,I/SS      ( 3650): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(4): G3s-1 a2:39:f7:70:12:80,
I/SS      ( 3650): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3650): 2015-11-24T10:43:56.856Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:43:56.857Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,V/GoogleAuthProtoRequest( 3731): [400] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [400] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [400] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3650): 2015-11-24T10:44:01.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:01.863Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:01.863Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:01.864Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3650): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  822): Explicit concurrent mark sweep GC freed 37049(1734KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.734ms total 89.874ms
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0,
,W/bt-btif ( 2394): invalid rfc slot id: 16
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:44:07.028Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:07.028Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:07.029Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
I/SS      ( 3650): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3650): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request,
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:44:12.031Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:12.032Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/BooksSync( 3587): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3587): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3587): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3587): Soft error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3587): Sync error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3587): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 574877, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3650): 2015-11-24T10:44:17.035Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:17.036Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:17.038Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:17.038Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at 90:E7:C4:F6:69:77,
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 17
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:44:22.199Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:22.200Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:22.201Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,D/btif_config( 2394): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1,
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2394): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
D/BluetoothAdapterProperties( 2394): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection
,I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 80 bytes.,
I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT1941","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
I/HS      ( 3650): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT1941
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT1941
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started,
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:44:26.361Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.760Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.768Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.772Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.775Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.784Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.809Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.814Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.826Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.859Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:44:26.866Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.870Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.887Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.918Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.943Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.953Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.961Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:26.998Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.014Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.020Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.054Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.088Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.109Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.119Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.126Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.159Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.166Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.203Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.204Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.219Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.259Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.263Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.271Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.308Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.325Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.332Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.407Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.426Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.450Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.481Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:44:27.487Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.518Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.522Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:27.524Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 13
I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT1941
,I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
,I/BtToSocketBase( 3650): Close local in
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT1941
,I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
,I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToSocketBase( 3650): Close bt socket
,I/jxcore-log( 3650): 2015-11-24T10:44:27.574Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0,
W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x46
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: ALE-L21
,V/GoogleAuthProtoRequest( 3731): [401] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3650): 2015-11-24T10:44:32.207Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:32.207Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:32.208Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:32.208Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3650): Starting to connect,
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/ExperimentUpdateService( 3731): [401] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3731): [401] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3650): Found 6 peers.
,I/SS      ( 3650): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3650): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3650): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2394): info:x10,
D/        ( 2394): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT2678, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT2678, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config( 2394): btif_get_device_type: Device [90:e7:c4:f6:69:77] type 1,
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1,
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: 90:E7:C4:F6:69:77,
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-rfcomm( 2394): PORT_StartCnf failed result:5
E/bt-btm  ( 2394): invalid rfc slot id: 19
,W/bt-btif ( 2394): invalid rfc slot id: 19
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:44:39.142Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:39.143Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:39.147Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
D/BluetoothMapService( 2394): onReceive
,I/jxcore-log( 3650): 2015-11-24T10:44:39.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:39.151Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:39.151Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:39.152Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): ,
,I/        ( 3650): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at 7C:F9:0E:37:96:AB
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 68656 ms, rnd: 5, ex: Connection to 90:E7:C4:F6:69:77 failed", source: file:///android_asset/www/js/thali_main.js (63),
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1543): Bluetooth Device Name: HTC One M8s,
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 20
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:44:44.294Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:44.295Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:44.296Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(6): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT2678, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT2678, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3650): 2015-11-24T10:44:49.297Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:49.298Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,D/btif_config( 2394): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: 7C:F9:0E:34:8A:A0,
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
I/BTListenerThread( 3650): we got incoming connection
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection,
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
,I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3650): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT1757
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, samsung-SM-G900F_PT1757
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
,I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/jxcore-log( 3650): 2015-11-24T10:44:50.143Z SendDataTCPServer.js: TCP/IP server connected
,I/jxcore-log( 3650): 
I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:44:50.577Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.584Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.589Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.611Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:44:50.621Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.658Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.664Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.673Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.708Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.713Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:44:50.748Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.757Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.789Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.793Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.802Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.838Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.872Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:50.874Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.887Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:50.890Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 18
,I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT1757
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close bt out
,I/BtToSocketBase( 3650): Close bt socket
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT1757
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,I/jxcore-log( 3650): 2015-11-24T10:44:51.031Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x4b
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3650): 2015-11-24T10:44:54.302Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:54.303Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:54.303Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:44:54.304Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: S5-1
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c,
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 22
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:44:59.941Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:59.942Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:44:59.942Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/ActivityManager(  822): Start proc 3954:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3954): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3954):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3954):   adb logcat -s GAv4
,W/GAv4    ( 3954): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3954): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3954): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3254:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,I/jxcore-log( 3650): 2015-11-24T10:45:04.944Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:04.944Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/jxcore-log( 3650): 2015-11-24T10:45:09.949Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:09.949Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:09.950Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:09.951Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Started service discovery,
,I/        ( 3650): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT2678, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT2678, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/art     ( 1428): Explicit concurrent mark sweep GC freed 57426(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.212ms total 32.614ms
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at blb.a(PG:3937)
E/HttpOperation( 3351): 	at czp.a(PG:18188)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 12 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 14 more
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at hec.a(PG:42)
E/HttpOperation( 3351): 	at hee.a(PG:102)
E/HttpOperation( 3351): 	at czr.a(PG:65)
E/HttpOperation( 3351): 	at kka.a(PG:108)
E/HttpOperation( 3351): 	at czp.a(PG:19176)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 15 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 17 more
,E/ExperimentLoader( 3351): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): 	at jdm.a(PG:82)
E/ExperimentLoader( 3351): 	at jcs.o(PG:406)
E/ExperimentLoader( 3351): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3351): 	,at jcs.i(PG:143)
E/ExperimentLoader( 3351): 	at hec.a(PG:42)
E/ExperimentLoader( 3351): 	at hee.a(PG:102)
E/ExperimentLoader( 3351): 	at czr.a(PG:65)
E/ExperimentLoader( 3351): 	at kka.a(PG:108)
E/ExperimentLoader( 3351): 	at czp.a(PG:19176),
E/ExperimentLoader( 3351): 	at czp.a(PG:9081)
E/ExperimentLoader( 3351): 	at czq.run(PG:1686)
E/ExperimentLoader( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 3351): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3351): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3351): 	at jdm.a(PG:77)
E/ExperimentLoader( 3351): 	... 15 more
E/ExperimentLoader( 3351): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3351): 	at fal.a(PG:38)
E/ExperimentLoader( 3351): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3351): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 610655, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 23
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:45:15.106Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:15.107Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:15.109Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:20.111Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:20.112Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86,
,I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/jxcore-log( 3650): 2015-11-24T10:45:25.116Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:25.117Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:25.118Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:25.118Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 7C:F9:0E:37:96:AB, name: null,
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to null, at 7C:F9:0E:37:96:AB
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT2678, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT2678, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT6835, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT6835, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 24
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:45:30.281Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): 2015-11-24T10:45:30.282Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:30.283Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,V/GoogleAuthProtoRequest( 3731): [402] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [402] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3731): [402] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3650): 2015-11-24T10:45:35.284Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:35.286Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config( 2394): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2394): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3650): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
I/HS      ( 3650): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT6835
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped,
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, samsung-SM-G800F_PT6835
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
,I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:45:36.427Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:36.947Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:36.950Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:36.958Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:36.961Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:36.991Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:36.996Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.001Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.039Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.045Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.068Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.108Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:45:37.115Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.122Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.126Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.153Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.188Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.193Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.200Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.239Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.242Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.270Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.308Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.322Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.350Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.388Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.392Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.492Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.496Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.528Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.597Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.603Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.638Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.773Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.892Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.900Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.905Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.938Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:37.942Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 21
,I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT6835
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT6835
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket,
,I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToSocketBase( 3650): Close bt in
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/jxcore-log( 3650): 2015-11-24T10:45:38.042Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x41
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3650): 2015-11-24T10:45:40.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:40.293Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
,I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:40.293Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:40.294Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at 7C:F9:0E:37:96:AB
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 26
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:45:45.955Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:45.957Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:45.963Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:45.967Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:45.968Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:45.969Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:45.969Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 3650): Connecting to null, at 34:FC:EF:11:AE:67
,I/BTConnectToThread( 3650): Starting to connect,
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 66808 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery,
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-rfcomm( 2394): PORT_StartCnf failed result:5
E/bt-btif ( 2394): PORT_StartCnf failed result:5
E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 2394): Device not in IRK list
E/bt-btif ( 2394): Do not find the bg connection mask for the remote device
W/bt-btif ( 2394): invalid rfc slot id: 27
,I/BluetoothBondStateMachine( 2394): No record of the device:null
I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 9 Address: 34:FC:EF:11:AE:67 newState: 0
E/BluetoothBondStateMachine( 2394): In stable state, received invalid newState: 10
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3650): 2015-11-24T10:45:51.167Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:45:51.167Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:51.168Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3650): 2015-11-24T10:45:56.169Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:45:56.170Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,D/btif_config( 2394): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State,
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3650): we got incoming connection
,I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
I/HS      ( 3650): Incoming connection Hand Shake finished for : LGE-LG-H815_PT8697
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, LGE-LG-H815_PT8697
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:45:59.708Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.366Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.372Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.378Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.472Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.575Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.632Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.637Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.836Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.868Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.922Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:00.991Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:01.120Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:01.173Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:01.174Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:01.175Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:01.175Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 34:FC:EF:11:AE:67, name: null,
,I/        ( 3650): Connecting to null, at 34:FC:EF:11:AE:67
I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3650): 2015-11-24T10:46:01.440Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data,
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6ebc rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:46:02.169Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:02.173Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:02.373Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:02.440Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,V/GoogleAuthProtoRequest( 3731): [403] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [403] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3731): [403] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93),
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6ebc rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,D/btif_config( 2394): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/jxcore-log( 3650): 2015-11-24T10:46:05.301Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3650): 
,I/        ( 3650): Started service discovery
,I/jxcore-log( 3650): 2015-11-24T10:46:05.591Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3650): 
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7084 rs_disc_pending=0
W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:46:05.979Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3650): 2015-11-24T10:46:06.135Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.183Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.413Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.734Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.739Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data,
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:46:06.785Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.791Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.843Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.847Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:06.851Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.027Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.314Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.319Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.365Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.397Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.745Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.750Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:07.925Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:08.291Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:08.294Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:08.680Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:08.697Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/jxcore-log( 3650): 2015-11-24T10:46:08.753Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:08.756Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3650): 
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7084 rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3650): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : LGE-Nexus 5_PT6925
I/HS      ( 3650): Hand Shake finished outgoing for : LGE-Nexus 5_PT6925
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, LGE-Nexus 5_PT6925
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): mHTTPPort  set to : 60496
,I/BtConnectorHelper( 3650): Request socket is using : 60496
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :60496
,I/jxcore-log( 3650): 2015-11-24T10:46:13.095Z SendDataConnector.js: CLIENT connected to 60496, error: null
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:13.096Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 60496,
I/BtToRequestSocket( 3650): Set local streams
I/BtToRequestSocket( 3650): rin ended ---------------------------;
,I/jxcore-log( 3650): 2015-11-24T10:46:13.111Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23853
,I/jxcore-log( 3650): 2015-11-24T10:46:13.568Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:13.863Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,I/jxcore-log( 3650): 2015-11-24T10:46:14.046Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6ebc rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:46:14.230Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:14.307Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:14.327Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data,
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053,
,I/jxcore-log( 3650): 2015-11-24T10:46:14.454Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:14.632Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:14.824Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:14.934Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:15.103Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:15.409Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:15.410Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:15.420Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:15.421Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
I/BtConnectorHelper( 3650): Disconnect outgoing peer: 34:FC:EF:11:AE:67
,I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3650): 2015-11-24T10:46:15.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:46:15.434Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:15.435Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:15.435Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 29443 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7084 rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [00:f4:6f:30:e0:6c]: 0, 0, 0
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7084 rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): dm_pm_timer expires,
W/bt-btif ( 2394): dm_pm_timer expires 0
W/bt-btif ( 2394): proc dm_pm_timer expires
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=0
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3650): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : samsung-SM-G800F_PT6835
,I/HS      ( 3650): Hand Shake finished outgoing for : samsung-SM-G800F_PT6835
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, samsung-SM-G800F_PT6835
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3650): mHTTPPort  set to : 44661
,I/BtConnectorHelper( 3650): Request socket is using : 44661
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :44661
,I/jxcore-log( 3650): 2015-11-24T10:46:23.390Z SendDataConnector.js: CLIENT connected to 44661, error: null
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:23.391Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 44661
,I/BtToRequestSocket( 3650): Set local streams
I/jxcore-log( 3650): 2015-11-24T10:46:23.399Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
I/BtToRequestSocket( 3650): rin ended ---------------------------;
,I/jxcore-log( 3650): 2015-11-24T10:46:23.458Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:23.519Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:23.748Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:23.882Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:24.079Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:24.181Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:24.251Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 25
,I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT8697
,I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream,
I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3650): 2015-11-24T10:46:24.277Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:46:24.886Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:25.078Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:25.188Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:25.254Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:25.345Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:25.539Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:25.886Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:46:26.286Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:26.287Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:26.294Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:26.295Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
,I/BtConnectorHelper( 3650): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
I/jxcore-log( 3650): 2015-11-24T10:46:26.305Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:26.313Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:26.317Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:26.317Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21,
,I/        ( 3650): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 10852 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: G4-1
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6cf4 rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa724c rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,D/btif_config( 2394): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1,
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3650): Incoming connection Hand Shake finished for : motorola-XT1072_PT8689
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, motorola-XT1072_PT8689
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:46:39.458Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:39.930Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:39.980Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.019Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.027Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.065Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.074Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.133Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.169Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.173Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.207Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.216Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.225Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.272Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.282Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.325Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.333Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.343Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.387Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.441Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.450Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.560Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.573Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.683Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.691Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.700Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.802Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.814Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.920Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.931Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.942Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.981Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.990Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:40.999Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.038Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.062Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.071Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.110Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.121Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.169Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.181Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.238Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.248Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.355Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.388Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.476Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3650): 2015-11-24T10:46:41.593Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.604Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.638Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.652Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.661Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:41.665Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 28
I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8689
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
,I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3650): 2015-11-24T10:46:41.800Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x4f
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x10  CID 0x4c
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 31
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:46:55.037Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:46:55.038Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:46:55.038Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:00.040Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:00.041Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL,
,D/btif_config( 2394): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
D/BluetoothAdapterProperties( 2394): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection,
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
I/HS      ( 3650): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2678
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2678
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/jxcore-log( 3650): 2015-11-24T10:47:03.707Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:47:04.089Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.096Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.107Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.153Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.157Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.165Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.173Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.210Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.217Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.252Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.258Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.263Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.298Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.317Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.322Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.327Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.333Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.337Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.369Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.374Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.378Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.419Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.444Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.457Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.467Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.472Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:04.474Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 32,
I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2678
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2678
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket,
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x40
I/jxcore-log( 3650): 2015-11-24T10:47:04.511Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3650): Found 6 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/jxcore-log( 3650): 2015-11-24T10:47:05.044Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:05.045Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:05.045Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:05.045Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3650): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7414 rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032,
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: A3-1
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x10  CID 0x42
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 34
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:47:16.469Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:16.470Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:16.472Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 4 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3650): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3650): 2015-11-24T10:47:21.475Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:21.476Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:26.480Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:26.481Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:26.481Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:26.482Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x10  CID 0x41
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0,
,W/bt-btif ( 2394): invalid rfc slot id: 35
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:47:31.758Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:31.759Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:31.760Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,V/GoogleAuthProtoRequest( 3731): [404] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [404] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3731): [404] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3650): 2015-11-24T10:47:36.762Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:36.763Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,D/btif_config( 2394): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 2394): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTListenerThread( 3650): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3650): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3650): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT3547
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, samsung-SM-A500FU_PT3547
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:47:38.694Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.077Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.114Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.121Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.127Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.132Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.141Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.163Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.198Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.203Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.238Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.269Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.275Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.281Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.318Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.321Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.329Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.368Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.373Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.379Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.434Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.440Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.449Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.457Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.469Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.520Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.526Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.535Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.551Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.560Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.598Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.607Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.639Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.669Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.673Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:39.708Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): invalid rfc slot id: 33
,I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT3547
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Close bt in
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close bt out
I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close bt socket
,I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT3547
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/jxcore-log( 3650): 2015-11-24T10:47:39.755Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
W/bt-rfcomm( 2394): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2394): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 3650): 2015-11-24T10:47:41.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:41.767Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:41.768Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:41.768Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3650): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6964 rs_disc_pending=1,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6964 rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: A5-1
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x10  CID 0x45
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 37
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:47:49.690Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:49.691Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:49.691Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3650): 2015-11-24T10:47:54.693Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:54.694Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:59.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:59.698Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:47:59.699Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:47:59.700Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  822): Explicit concurrent mark sweep GC freed 44691(2034KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.950ms total 80.721ms
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x10  CID 0x46
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 38
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:48:04.985Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:04.986Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:04.991Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:05.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- round done--------,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:05.003Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:05.003Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:05.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: F4:F1:E1:5C:3B:E2, name: null,
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at F4:F1:E1:5C:3B:E2,
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 98670 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config( 2394): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: F4:F1:E1:5C:3B:E2,
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3650): Starting to Handshake
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTConnectToThread( 3650): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : motorola-XT1039_PT179
,I/HS      ( 3650): Hand Shake finished outgoing for : motorola-XT1039_PT179
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, motorola-XT1039_PT179
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): mHTTPPort  set to : 43078
,I/BtConnectorHelper( 3650): Request socket is using : 43078
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :43078
,I/jxcore-log( 3650): 2015-11-24T10:48:06.650Z SendDataConnector.js: CLIENT connected to 43078, error: null
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:06.651Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:06.659Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 43078
I/BtToRequestSocket( 3650): Set local streams
I/BtToRequestSocket( 3650): rin ended ---------------------------;
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:408
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3650): 2015-11-24T10:48:06.770Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:06.773Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3650): 2015-11-24T10:48:06.871Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:06.885Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:06.915Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:06.927Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.022Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.027Z SendDataConnector.js: CLIENT is data received : 80000
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.076Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.109Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.110Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:07.111Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:07.112Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
,I/BtConnectorHelper( 3650): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2,
I/BtToSocketBase( 3650): Stop ReceivingThread,
I/BtToSocketBase( 3650): Stop SendingThread,
I/BtToSocketBase( 3650): Close local in,
,I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket,
I/BtToSocketBase( 3650): Close bt in,
I/BtToSocketBase( 3650): Close bt out,
I/BtToSocketBase( 3650): Close bt socket,
I/BtToRequestSocket( 3650): Close server socket
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3650): 2015-11-24T10:48:07.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.117Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.118Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:07.118Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 2107 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND,
,W/bt-btif ( 2394): info:x10,
D/        ( 2394): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa75dc rs_disc_pending=0
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3650): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
,I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTConnectToThread( 3650): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : samsung-SM-G900F_PT1757
I/HS      ( 3650): Hand Shake finished outgoing for : samsung-SM-G900F_PT1757
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, samsung-SM-G900F_PT1757
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3650): mHTTPPort  set to : 33239
,I/BtConnectorHelper( 3650): Request socket is using : 33239
I/BtToRequestSocket( 3650): Now accepting connections
,I/        ( 3650): Started service discovery
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :33239
,I/jxcore-log( 3650): 2015-11-24T10:48:11.851Z SendDataConnector.js: CLIENT connected to 33239, error: null
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:48:11.852Z SendDataConnector.js: CLIENT starting client ,
,I/jxcore-log( 3650): 
I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 33239
I/BtToRequestSocket( 3650): Set local streams
I/BtToRequestSocket( 3650): rin ended ---------------------------;
I/jxcore-log( 3650): 2015-11-24T10:48:11.862Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: XT1039
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3650): 2015-11-24T10:48:13.752Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:13.816Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:13.894Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:13.978Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:14.045Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3650): we got incoming connection
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTListenerThread( 3650): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3650): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3650): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3650): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3650): Incoming connection Hand Shake finished for : motorola-XT1039_PT179
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : true, motorola-XT1039_PT179
,I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3650): Creating BTConnectedThread
I/BtConnectorHelper( 3650): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3650): --DoOneRunRound started
,I/BtToRequestSocket( 3650): LocalHost address: localhost/127.0.0.1, port: 57332
,I/jxcore-log( 3650): 2015-11-24T10:48:15.289Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): --DoOneRunRound ended
,I/jxcore-log( 3650): 2015-11-24T10:48:15.295Z SendDataConnector.js: CLIENT is data received : 60000
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:15.428Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3650): 
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:48:15.960Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:15.983Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:16.057Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:16.199Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:16.199Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:16.208Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:16.209Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
,I/BtConnectorHelper( 3650): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3650): Stop ReceivingThread
,I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,I/BtToRequestSocket( 3650): Close server socket
,I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3650): 2015-11-24T10:48:16.216Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:16.220Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:16.221Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:16.221Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: F8:95:C7:87:3C:51, name: G4-1
I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to G4-1, at F8:95:C7:87:3C:51
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 9084 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/        ( 3650): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6925, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6925, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/jxcore-log( 3650): 2015-11-24T10:48:17.358Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:17.617Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: G4-1
,W/bt-btif ( 2394): info:x10
D/        ( 2394): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3650): 2015-11-24T10:48:17.843Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3650): 
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa6b2c rs_disc_pending=1,
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa77a4 rs_disc_pending=0,
W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:48:18.350Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
,I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:18.385Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3650): 2015-11-24T10:48:18.559Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:18.699Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:18.899Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3650): 
,D/btif_config( 2394): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2394): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/jxcore-log( 3650): 2015-11-24T10:48:19.307Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3650): 
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,I/jxcore-log( 3650): 2015-11-24T10:48:19.339Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:19.463Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:19.498Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:19.547Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3650): 
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/jxcore-log( 3650): 2015-11-24T10:48:19.708Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:19.741Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:19.854Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3650): 
,I/BTConnectToThread( 3650): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : LGE-LG-H815_PT8697
I/HS      ( 3650): Hand Shake finished outgoing for : LGE-LG-H815_PT8697
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, LGE-LG-H815_PT8697
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): mHTTPPort  set to : 32909
I/BtConnectorHelper( 3650): Request socket is using : 32909
I/BtToRequestSocket( 3650): Now accepting connections
,I/jxcore-log( 3650): 2015-11-24T10:48:19.893Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa77a4 rs_disc_pending=1
,W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3650): 2015-11-24T10:48:20.028Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.057Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.063Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.070Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.108Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.171Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3650): 
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :32909
,I/jxcore-log( 3650): 2015-11-24T10:48:20.184Z SendDataConnector.js: CLIENT connected to 32909, error: null
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:20.184Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 32909
,I/BtToRequestSocket( 3650): Set local streams
,I/jxcore-log( 3650): 2015-11-24T10:48:20.194Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.196Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): rin ended ---------------------------;
,I/jxcore-log( 3650): 2015-11-24T10:48:20.239Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.278Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3650): 
,D/        ( 2394): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 3650): 2015-11-24T10:48:20.332Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.349Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.371Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.445Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.499Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.505Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.531Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.646Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.678Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3650): 
,D/btif_config( 2394): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
I/BluetoothBondStateMachine( 2394): sspRequestCallback: [B@23c012ba name: [B@3458d56b cod: 5898764 pairingVariant 0 passkey: 164915
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2394): Entering PendingCommandState State
,I/jxcore-log( 3650): 2015-11-24T10:48:20.777Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.794Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.926Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:20.929Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.053Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.080Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.123Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.146Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3650): ,
,I/jxcore-log( 3650): 2015-11-24T10:48:21.158Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.206Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.216Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.222Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.281Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3650): 
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: S5-1
,E/qti_sensors_hal(  822): waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
E/qti_sensors_hal(  822): deactivateDpc: ERROR: No response from the request
,I/jxcore-log( 3650): 2015-11-24T10:48:21.560Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.593Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.618Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.633Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.793Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.804Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.874Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:21.917Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:22.121Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:48:22.750Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:22.751Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:22.755Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:22.755Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
,I/BtConnectorHelper( 3650): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
,I/jxcore-log( 3650): 2015-11-24T10:48:22.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:22.768Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:22.768Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:22.768Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to A3-1, at 08:EC:A9:50:75:41
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 6531 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [08:ec:a9:50:75:41]: 7, f, 610c
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: A3-1
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7414 rs_disc_pending=0
,W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2394): onReceive,
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: G4-1
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7414 rs_disc_pending=1
,E/bt-btm  ( 2394): invalid rfc slot id: 43
W/bt-btif ( 2394): invalid rfc slot id: 43
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3650): 2015-11-24T10:48:26.740Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:26.741Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
D/BluetoothMapService( 2394): onReceive
I/jxcore-log( 3650): 2015-11-24T10:48:26.742Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: A3-1
,W/bt-btif ( 2394): dm_pm_timer expires
,W/bt-btif ( 2394): dm_pm_timer expires 0
W/bt-btif ( 2394): proc dm_pm_timer expires
,I/jxcore-log( 3650): 2015-11-24T10:48:31.748Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:31.749Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT4125, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT4125, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3650): 2015-11-24T10:48:36.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:36.752Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:36.753Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:36.754Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to A3-1, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10,
D/        ( 2394): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: A3-1
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa7414 rs_disc_pending=1
W/bt-btif ( 2394): bta_dm_check_av:0,
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): invalid rfc slot id: 44
W/bt-btif ( 2394): invalid rfc slot id: 44
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:48:41.255Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
,I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:41.255Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:41.256Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1543): Bluetooth Device Name: A3-1,
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 10 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT4125, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT4125, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): 2015-11-24T10:48:46.259Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:46.260Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa77a4 rs_disc_pending=0
E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2394): Device not in IRK list
E/bt-btif ( 2394): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 2394): bta_dm_check_av:0
E/bt-btif ( 2394): Do not find the bg connection mask for the remote device
,I/BluetoothBondStateMachine( 2394): bondStateChangeCallback: Status: 9 Address: 80:01:84:8A:B3:68 newState: 0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
D/BluetoothAdapterProperties( 2394): Failed to remove device: 80:01:84:8A:B3:68
,D/BluetoothMapService( 2394): onReceive
,I/BluetoothBondStateMachine( 2394): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2394): StableState(): Entering Off State
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3650): 2015-11-24T10:48:51.264Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:48:51.265Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:51.265Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:48:51.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
I/        ( 3650): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to A3-1, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 10 peers.
,I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT4125, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT4125, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x1f  CID 0x46
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 45
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:49:01.257Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:01.258Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:01.258Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:06.259Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:06.260Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 10 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/jxcore-log( 3650): 2015-11-24T10:49:11.264Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:11.265Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:11.265Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:11.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to A3-1, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): invalid rfc slot id: 36
,E/bt-btm  ( 2394): invalid rfc slot id: 36
,I/BtToSocketBase( 3650): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT179
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread,
I/BtToSocketBase( 3650): Close local in
,I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
,I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3650): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3650): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT179
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/jxcore-log( 3650): 2015-11-24T10:49:11.606Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3650): 
D/BluetoothMapService( 2394): onReceive
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: XT1039
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT4125, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT4125, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 46
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:49:16.427Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:16.429Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:16.430Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:21.430Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:21.431Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/jxcore-log( 3650): 2015-11-24T10:49:26.436Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:26.437Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:26.437Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:26.438Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3650): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 10 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3650): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT4125, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT4125, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b,
,I/        ( 3650): Cleared service requests,
I/        ( 3650): Started peer discovery
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 8 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac,
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3650): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a,
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 47
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:49:57.625Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:57.625Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:57.631Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:57.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:57.642Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:57.643Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:57.643Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3650): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 94859 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 48
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:49:58.923Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:49:58.924Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:49:58.925Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa77a4 rs_disc_pending=0
E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/        ( 3650): Cleared service requests
I/        ( 3650): Started peer discovery
,I/jxcore-log( 3650): 2015-11-24T10:50:03.925Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:50:03.926Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:50:08.930Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:50:08.931Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:50:08.931Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:50:08.932Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3650): Starting to connect
,I/        ( 3650): Connecting to null, at 08:EC:A9:50:76:27
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 8 peers.,
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
,I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/GCM     ( 1819): Message from null null
E/GCM     ( 1819): Dropping message from null
,D/GCM     ( 1428): Message class com.google.f.a.a.i
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/SS      ( 3650): Found 4 peers.
I/SS      ( 3650): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x48
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 49
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:51:01.821Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:51:01.821Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:51:01.822Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 4 peers.,
I/SS      ( 3650): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:51:06.823Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:51:06.824Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:51:11.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:51:11.829Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:51:11.830Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:51:11.830Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:76:27, name: null,
,I/BTConnectToThread( 3650): Starting to connect,
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,V/GoogleAuthProtoRequest( 3731): [405] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [405] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [405] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,V/KeepSync( 3556): Connecting to GoogleApiClient
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3556): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3556): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3556): IOException
,E/KeepSync( 3556): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3556): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3556): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3556): 	,at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3556): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3556): ,	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3556): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3556): 	,at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3556): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3556): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3556): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3556): 	... 10 more
W/KeepSync( 3556): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1045867, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4b
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 50,
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3650): 2015-11-24T10:52:05.742Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:05.743Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:05.745Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3650): 2015-11-24T10:52:10.747Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:10.748Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:15.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:15.753Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:15.754Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:15.754Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,W/bt-btif ( 2394): info:x10,
D/        ( 2394): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 51
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:52:19.689Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:19.689Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:19.690Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa77a4 rs_disc_pending=0
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2394): bta_dm_check_av:0
W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3650): 2015-11-24T10:52:24.691Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:24.691Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3650): 2015-11-24T10:52:29.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:29.697Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.698Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.698Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2394): invalid rfc slot id: 52
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:52:29.945Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.946Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.949Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:29.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.955Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.955Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:29.956Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to XT1072, at 44:80:EB:7B:5A:05
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 152304 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2394): info:x10
,D/        ( 2394): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2394): process_service_search_attr_rsp
,W/bt-btif ( 2394): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2394): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2394): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3650): Starting to Handshake
,I/BTHandshakeSocketThread( 3650): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3650): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread started
,I/BTConnectToThread( 3650): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3650): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3650): HandshakeOk : motorola-XT1072_PT8689
I/HS      ( 3650): Hand Shake finished outgoing for : motorola-XT1072_PT8689
I/BTHandshakeSocketThread( 3650): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3650): Starting the connected thread incoming : false, motorola-XT1072_PT8689
I/BtToSocketBase( 3650): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3650): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3650): mHTTPPort  set to : 45178
I/BtConnectorHelper( 3650): Request socket is using : 45178
I/BtToRequestSocket( 3650): Now accepting connections
,I/BtConnectorHelper( 3650): Calling ConnectionStatusUpdate with port :45178
I/jxcore-log( 3650): 2015-11-24T10:52:31.709Z SendDataConnector.js: CLIENT connected to 45178, error: null,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:31.710Z SendDataConnector.js: CLIENT starting client 
,I/jxcore-log( 3650): 
,I/BtToRequestSocket( 3650): incoming data from: /127.0.0.1, port: 45178
I/BtToRequestSocket( 3650): Set local streams
,I/jxcore-log( 3650): 2015-11-24T10:52:31.719Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3650): 
I/BtToRequestSocket( 3650): rin ended ---------------------------;
,E/bt-btm  ( 2394): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2394): aclStateChangeCallback: Device is NULL
,I/BooksSync( 3587): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3587): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3587): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3587): Soft error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3587): Sync error
E/BooksSync( 3587): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3587): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3587): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1074455, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 2394): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.,
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8,
I/SS      ( 3650): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3650): 2015-11-24T10:52:41.766Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:41.767Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:41.768Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:41.769Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:41.770Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3650): 
,I/BtToSocketBase( 3650): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3650): Disconnect outgoing peer: motorola-XT1072_PT8689
I/BtToSocketBase( 3650): Stop ReceivingThread
I/BtToSocketBase( 3650): Stop SendingThread
I/BtToSocketBase( 3650): Close local in
I/BtToSocketBase( 3650): Close LocalOutputStream
,I/BtToSocketBase( 3650): Close localHostSocket
I/BtToSocketBase( 3650): Close bt in
I/BtToSocketBase( 3650): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3650): Close bt out
I/BtToSocketBase( 3650): Close bt socket
I/BtToRequestSocket( 3650): Close server socket
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3650): 2015-11-24T10:52:46.771Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:46.771Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:51.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:52:51.777Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:51.777Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:52:51.778Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 44:80:EB:7B:5A:05, name: XT1072,
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to XT1072, at 44:80:EB:7B:5A:05
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2394): tBTM_SEC_DEV:0xa2fa724c rs_disc_pending=0
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 2394): invalid rfc slot id: 54
,W/bt-btif ( 2394): invalid rfc slot id: 54
,W/bt-btif ( 2394): bta_dm_check_av:0
,W/bt-btif ( 2394): btif_dm_cback : unhandled event (14)
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:53:02.078Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:53:02.079Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:02.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3650): 
D/BluetoothMapService( 2394): onReceive
,I/BTConnectionReceiver( 1543): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1543): Bluetooth Device Name: XT1072
,I/        ( 3650): Cleared service requests
I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:53:07.080Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:07.081Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:53:12.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:53:12.086Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:12.086Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:12.087Z SendDataConnector.js: do connect now
,I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback,
,I/        ( 3650): Connecting to XT1072, at 44:80:EB:7B:5A:05,
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 55
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:53:42.852Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:42.853Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:42.854Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/art     ( 1428): Explicit concurrent mark sweep GC freed 68751(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 27MB/43MB, paused 1.541ms total 63.186ms
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at blb.a(PG:3937)
E/HttpOperation( 3351): 	at czp.a(PG:18188)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 12 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 14 more
,I/art     (  822): Explicit concurrent mark sweep GC freed 57061(2MB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.604ms total 74.066ms
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3351): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3351): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3351): 	at jdm.a(PG:82)
E/HttpOperation( 3351): 	at jcs.o(PG:406)
E/HttpOperation( 3351): 	at jcn.a(PG:1379)
E/HttpOperation( 3351): 	at jcs.i(PG:143)
E/HttpOperation( 3351): 	at hec.a(PG:42)
E/HttpOperation( 3351): 	at hee.a(PG:102)
E/HttpOperation( 3351): 	at czr.a(PG:65)
E/HttpOperation( 3351): 	at kka.a(PG:108)
E/HttpOperation( 3351): 	at czp.a(PG:19176)
E/HttpOperation( 3351): 	at czp.a(PG:9081)
E/HttpOperation( 3351): 	at czq.run(PG:1686)
E/HttpOperation( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3351): 	at jdj.a(PG:4091)
E/HttpOperation( 3351): 	at jdj.a(PG:1125)
E/HttpOperation( 3351): 	at jdm.a(PG:77)
E/HttpOperation( 3351): 	... 15 more
E/HttpOperation( 3351): Caused by: faj: BadAuthentication
E/HttpOperation( 3351): 	at fal.a(PG:38)
E/HttpOperation( 3351): 	at jdj.a(PG:4089)
E/HttpOperation( 3351): 	... 17 more
E/ExperimentLoader( 3351): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3351): 	at jdm.a(PG:82)
E/ExperimentLoader( 3351): 	at jcs.o(PG:406)
E/ExperimentLoader( 3351): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3351): 	at jcs.i(PG:143)
E/ExperimentLoader( 3351): 	at hec.a(PG:42)
E/ExperimentLoader( 3351): 	at hee.a(PG:102)
E/ExperimentLoader( 3351): 	at czr.a(PG:65)
E/ExperimentLoader( 3351): 	at kka.a(PG:108)
E/ExperimentLoader( 3351): 	at czp.a(PG:19176)
E/ExperimentLoader( 3351): 	at czp.a(PG:9081)
E/ExperimentLoader( 3351): 	at czq.run(PG:1686)
E/ExperimentLoader( 3351): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3351): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3351): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3351): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3351): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3351): 	at jdm.a(PG:77)
E/ExperimentLoader( 3351): 	... 15 more
E/ExperimentLoader( 3351): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 3351): 	at fal.a(PG:38)
E/ExperimentLoader( 3351): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3351): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1145759, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): 2015-11-24T10:53:47.855Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:47.856Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:53:52.860Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:53:52.861Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:53:52.862Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:53:52.862Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/BTConnectToThread( 3650): Starting to connect,
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to XT1072, at 44:80:EB:7B:5A:05
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,V/GoogleAuthProtoRequest( 3731): [406] a.<init>: mAccountName set to: thalitester@gmail.com
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/EventLogService( 1819): Opted in for usage reporting
I/EventLogService( 1819): Aggregate from 1448360652102 (log), 1448360652102 (data)
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [406] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [406] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,W/EventLogAggregator( 1819): Unknown tag: snet_gcore
W/EventLogAggregator( 1819): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1819): dumping service [account]
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 56
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:54:23.838Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:23.839Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:23.840Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3650): Cleared service requests,
,I/        ( 3650): Started peer discovery
,I/jxcore-log( 3650): 2015-11-24T10:54:28.841Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:28.842Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
,I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:54:33.846Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:33.847Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:33.847Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:33.848Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to XT1072, at 44:80:EB:7B:5A:05
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 57
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:54:39.010Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:39.027Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:39.029Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:39.029Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:39.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:39.033Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:39.033Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:39.033Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3650): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 129072 ms, rnd: 5, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
,E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 58
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:54:44.178Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:44.180Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:44.180Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/jxcore-log( 3650): 2015-11-24T10:54:49.182Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:49.183Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:54.186Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:54.187Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:54:54.188Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:54:54.188Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3650): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68,
I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x46
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 59
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:55:28.124Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:55:28.124Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:55:28.125Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.,
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): Note3-1 ea:50:8b:de:28:a3,
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3650): 2015-11-24T10:55:33.126Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:55:33.127Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3650): 2015-11-24T10:55:38.130Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:55:38.130Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:55:38.131Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:55:38.131Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6925, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6925, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 9 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4c
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 60
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:56:09.041Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:56:09.041Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:56:09.042Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:56:14.043Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:56:14.044Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/jxcore-log( 3650): 2015-11-24T10:56:19.047Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:56:19.048Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:56:19.049Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:56:19.049Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820,
,I/        ( 3650): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68,
I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 9 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 9 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x49,
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 61
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3650): 2015-11-24T10:56:50.005Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:56:50.005Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:56:50.006Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 9 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:56:55.008Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:56:55.009Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3650): 2015-11-24T10:57:00.014Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): 2015-11-24T10:57:00.015Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:57:00.016Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): 2015-11-24T10:57:00.017Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3650): Starting to connect,
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 9 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 3650): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6925, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6925, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 62
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:57:30.984Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:57:30.985Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:57:30.988Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:57:30.992Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- round done--------
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): do fake peer & start
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:57:30.995Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:57:30.996Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:57:30.997Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback round[0] time: 171953 ms, rnd: 5, ex: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:,
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3650): Cleared service requests,
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 63
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:58:01.661Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:01.662Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:01.663Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:06.665Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:58:06.665Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:11.669Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:58:11.670Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:11.671Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:58:11.671Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3650): timeout now
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): dun
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): weAreDoneNow , resultArray.length: 9
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): done, now sending data to server
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): -- RESULT DATA {"name:":"motorola-Nexus 6_PT1620","time":1000099,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:1F:C9:5E","time":9404,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:14:E2:C0","time":64727,"result":"OK","connections":3,"tryCount":1},{"name":"F8:95:C7:87:85:54","time":24027,"result":"OK","connections":2,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":17306,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:11:AE:67","time":29443,"result":"OK","connections":2,"tryCount":1},{"name":"00:F4:6F:30:E0:6C","time":10852,"result":"OK","connections":1,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":2107,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":9084,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":6531,"result":"OK","connections":1,"tryCount":1},{"connections":2,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":1,"name":"5
,I/jxcore-log( 3650): sendList : 100% : 64727 ms, 99% : 64727 ms, 95 : 64727 ms, 90% : 29443 ms.
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Result count 9, range 2107 ms to  64727 ms.
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): sendList failed peers count : 7 [43.75 %]
I/jxcore-log( 3650): 
I/jxcore-log( 3650): - Peer ID : 90:E7:C4:F6:69:77, Tried : 2
I/jxcore-log( 3650): 
I/jxcore-log( 3650): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
,I/jxcore-log( 3650): 
I/jxcore-log( 3650): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 3650): 
I/jxcore-log( 3650): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:14.980Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:58:14.981Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x48
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 64
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T10:58:42.627Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:42.628Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:58:42.630Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/jxcore-log( 3650): 2015-11-24T10:58:47.631Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:47.632Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/jxcore-log( 3650): 2015-11-24T10:58:52.636Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:52.637Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:58:52.637Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:58:52.638Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3650): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 5 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Started service discovery
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 7 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6925, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6925, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4b
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2394): invalid rfc slot id: 65
,I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3650): 2015-11-24T10:59:23.579Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:59:23.580Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:59:23.580Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): 2015-11-24T10:59:28.582Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:59:28.583Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,V/GoogleAuthProtoRequest( 3731): [407] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1428): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1428): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1428): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1428): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1428): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3731): [407] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3731): [407] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,W/ExperimentUpdateService( 3731): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3731): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3731): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3731): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3731): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3650): 2015-11-24T10:59:33.588Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T10:59:33.588Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): ,
I/jxcore-log( 3650): 2015-11-24T10:59:33.589Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T10:59:33.589Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s,
,I/BTConnectToThread( 3650): Starting to connect
,W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.
,I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0,
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3650): Found 8 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(6): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3650): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4f
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 66
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T11:00:04.549Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T11:00:04.550Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T11:00:04.551Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3650): 
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3650): 2015-11-24T11:00:09.551Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T11:00:09.552Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T11:00:14.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T11:00:14.557Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T11:00:14.557Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T11:00:14.558Z SendDataConnector.js: do connect now
I/jxcore-log( 3650): 
,I/        ( 3650): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/BTConnectToThread( 3650): Starting to connect
W/BluetoothAdapter( 3650): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3650): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2394): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3650): Found 8 peers.
,I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3650): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2394): SDP - Rcvd conn cnf with error: 0x8  CID 0x4e
E/bt-btif ( 2394): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2394): invalid rfc slot id: 67
I/BTConnectToThread( 3650): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3650): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3650): 2015-11-24T11:00:45.498Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T11:00:45.498Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T11:00:45.499Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3650): 
I/jxcore-log( 3650): 2015-11-24T11:00:45.502Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3650): 
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 3 peers.,
I/SS      ( 3650): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3650): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3650): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btm  ( 2394): Stopping oneshot timer
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Cleared service requests
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 6 peers.,
I/SS      ( 3650): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3650): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/        ( 3650): Started service discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3650): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3650): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 2394): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3650): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Cleared service requests
I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started peer discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 8 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3650): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3650): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3650): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3650): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3650): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3650): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT5312, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3650): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT5312, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3650): Cleared service requests
,I/        ( 3650): Started peer discovery,
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3650): Found 8 peers.
I/SS      ( 3650): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3650): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3650): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3650): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3650): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3650): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3650): Peer(7): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3650): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3650): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3650): Added service request
,I/wpa_supplicant( 1183): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3650): Started service discovery
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1183): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3650): DBG, CoordinatorConnector command called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): stop tests now !
I/jxcore-log( 3650): 
I/jxcore-log( 3650): stop current!
I/jxcore-log( 3650): 
I/jxcore-log( 3650): testSendData stopped
I/jxcore-log( 3650): 
I/        ( 3650): Stoping All
I/        ( 3650): Stopping services
I/        ( 3650): Stopping services
I/        ( 3650): Stop Bluetooth
I/        ( 3650): Stop Bluetooth
,I/BTListenerThread( 3650): Stopped,
I/jxcore-log( 3650): StopBroadcasting went ok
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): 2015-11-24T11:02:34.380Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3650): 
,I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3650): DBG, CoordinatorConnector command called
I/jxcore-log( 3650): 
,I/jxcore-log( 3650): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":2107,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:3C:51\",\"time\":6531,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":9084,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":9404,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":10852,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":17306,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:85:54\",\"time\":24027,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"34:FC:EF:11:AE:67\",\"time\":29443,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":64727,\"result\":\"OK\",\"connections\":3,\"tryCount\":1}],\"sendError\":{\"failedPeer\":[{\"conne,
I/jxcore-log( 3650): ****TEST TOOK:  ms ****
I/jxcore-log( 3650): 
I/jxcore-log( 3650): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3650): 
I/jxcore-log( 3650): stop tests now !,
I/jxcore-log( 3650): 
I/jxcore-log( 3650): end, event received
I/jxcore-log( 3650): 
I/jxcore-log( 3650): CoordinatorConnector close called
I/jxcore-log( 3650): 
I/jxcore-log( 3650): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3650): 
I/jxcore-log( 3650): The Coordinator has disconnected!
I/jxcore-log( 3650): 
I/jxcore-log( 3650): The Coordinator has closed!
I/jxcore-log( 3650): 
I/jxcore-log( 3650): stop tests now !
I/jxcore-log( 3650): 
I/jxcore-log( 3650): turning Radios off
I/jxcore-log( 3650): 
I/jxcore-log( 3650): Toggling radios to false
I/jxcore-log( 3650): 
D/BluetoothAdapter( 3650): enable(): BT is already enabled..!
I/chromium( 3650): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime( 4284): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4284): CheckJNI is OFF
,D/AndroidRuntime( 4284): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  822): Killing 3650:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{11255d07 com.example.hello/10272} due to missing metadata
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3650
,D/WifiService(  822): Client connection lost with reason: 4
,W/ActivityManager(  822): Force removing ActivityRecord{2913ab70 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,W/WindowManager(  822): Failed looking up window
W/WindowManager(  822): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@1a4b2fda does not exist
W/WindowManager(  822): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  822): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  822): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  822): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,I/WindowState(  822): WIN DEATH: null
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/TaskPersister(  822): removeObsoleteFile: deleting file=24_task.xml
D/BuaReceiver( 3438): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1248): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1248): run()
,I/Decoder ( 1248): createOrResetDecoder
,D/VoicemailCleanupService( 2744): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  822): Start proc 4303:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/art     (  822): Explicit concurrent mark sweep GC freed 62910(3MB) AllocSpace objects, 11(364KB) LOS objects, 31% free, 34MB/50MB, paused 1.788ms total 81.108ms
,I/art     ( 1062): Explicit concurrent mark sweep GC freed 76091(3MB) AllocSpace objects, 1(30MB) LOS objects, 17% free, 73MB/89MB, paused 2.007ms total 85.310ms
I/art     (  822): WaitForGcToComplete blocked for 88.846ms for cause Explicit
,I/ConfigService( 1428): onCreate
,I/art     ( 1543): Explicit concurrent mark sweep GC freed 77482(3MB) AllocSpace objects, 18(288KB) LOS objects, 37% free, 26MB/42MB, paused 554us total 122.172ms
I/art     ( 1543): WaitForGcToComplete blocked for 39.708ms for cause HeapTrim
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1248): run()
,W/ContextImpl( 4303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1428): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1428): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3650 uid 10265
,I/Keyboard.Facilitator( 1248): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1248): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1248): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1248): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1248): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1248): run()
I/StatsUtilsManager( 1248): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1248): shouldRecordStats() = Too Soon
,W/LocationOracleImpl( 1543): Best location was null
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     ( 1402): Explicit concurrent mark sweep GC freed 4961(361KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.177ms total 34.683ms
,D/PackageBroadcastService( 1819): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1819): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1819): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1819): Clearing selected account for com.test.thalitest
,D/AsyncChannel(  822): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
I/HotwordRecognitionRnr( 1543): Starting hotword detection.
W/System.err(  822): android.os.DeadObjectException
W/System.err(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  822): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  822): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  822): 	at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$P2pEnabledState.processMessage(WifiP2pServiceImpl.java:1116)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
W/System.err(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  822): 	at android.os.Looper.loop(Looper.java:135)
W/System.err(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/wpa_supplicant( 1183): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1183): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/MicrophoneInputStream( 1543): mic_starting com.google.android.apps.gsa.speech.audio.u@234bd2b1
D/ChimeraCfgMgr( 1819): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1819): Module APK com.google.android.play.games already loaded
,I/AudioFlinger(  357): AudioFlinger's thread 0xb4cd4000 ready to run
,D/AsyncChannel(  822): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
W/System.err(  822): android.os.DeadObjectException
,W/System.err(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  822): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  822): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  822): 	at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$InactiveState.processMessage(WifiP2pServiceImpl.java:1244)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
W/System.err(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  822): ,	at android.os.Looper.loop(Looper.java:135)
W/System.err(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1543): mic_started com.google.android.apps.gsa.speech.audio.u@234bd2b1
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,I/LocationSettingsChecker( 1819): Removing dialog suppression flag for package com.test.thalitest
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,D/Launcher.Workspace( 1402): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1402): 11683562 - stripEmptyScreens()
I/UpdateIcingCorporaServi( 1543): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  822): Explicit concurrent mark sweep GC freed 10852(539KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 2.950ms total 172.324ms
,D/GOOGLEHELP_CompatibleDatabase( 1819): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1819): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1819): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1819): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 1819): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1819): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1819): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/LocationOracleImpl( 1543): Best location was null
,D/GOOGLEHELP_CompatibleDatabase( 1819): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1819): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,I/ConfigFetchService( 1819): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 1819): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1819): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1819): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1819): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1819): Using Auth Proxy for data requests.
,W/BaseAppContext( 1819): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1819): CP2 sync disabled
,W/LocationOracleImpl( 1543): Best location was null
,I/ConfigFetchService( 1819): service connected
,I/Icing   ( 1819): doRemovePackageData com.test.thalitest
,I/HotwordWorker( 1543): onReady
,W/Launcher( 1402): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1cfc1202 new=com.google.android.velvet.VelvetApplication@1cfc1202
,I/UpdateIcingCorporaServi( 1543): UpdateCorporaTask done [took 85 ms] updated apps [took 85 ms] 
,I/art     ( 1843): Explicit concurrent mark sweep GC freed 20873(1212KB) AllocSpace objects, 11(176KB) LOS objects, 37% free, 26MB/42MB, paused 901us total 48.916ms
,E/DataBuffer( 1843): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32a2ffe1)
,I/ActivityManager(  822): Start proc 4358:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@133c22a1}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=23.50 rxSuccessRate=30.00 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=90.75 rxSuccessRate=263.50 targetRoamBSSID=any RSSI=-44
,I/art     ( 4284): System.exit called, status: 0
I/AndroidRuntime( 4284): VM exiting with result code 0.
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703081235
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  822): Start proc 4379:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  822): Killing 3226:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/kickstart(  877): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  877): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  877): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  877): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/ExternalStorage( 4379): After updating volumes, found 1 active roots
,W/ResourcesManager( 3505): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3505): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 4358): Update found 7 roots in 320ms
,D/Documents( 4358): Update found 7 roots in 131ms
,E/native  ( 1248): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1248): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1248): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1248): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1248): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1248): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1248): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1248): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/Icing   ( 1819): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox,
,E/Icing   ( 1819): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1819): Could not init tag ds.tag.deleted
,E/Icing   ( 1819): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1819): Could not init tag ds.tag.deleted
,I/Icing   ( 1819): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
,E/Icing   ( 1819): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1819): Writing status failed
,E/Icing   ( 1819): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
,I/kickstart(  877): WARNING: function: sahara_start:892 Retrying memory read request
,E/Search.SharedPreferencesProto( 1543): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ConfigService( 1428): onDestroy
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@133c22a1}
,E/kickstart(  877): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
E/kickstart(  877): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  877): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,E/ThermalEngine(  365): qmi_clnt_error_cb: with error -2 called for clnt FUSION
D/        (  357): csd_client_error_cb: error -2 cb_data 0xb6044060,
D/        (  357): csd_client_error_cb: MDM reset
E/ThermalEngine(  365): modem_clnt_error_cb: with -2 called for clnt 0x7
E/        (  357): deinit: QMI - result 0, error 0, CSD - valid 0, status 0, rc -2
E/        (  357): csd_service_deinit: Error -1 deiniting CSD
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb0
I/Atfwd_Daemon(  374): Modem Out Of Service --> Release ATCOP service client handles, if any
I/Atfwd_Daemon(  374): release_client returns -1, qmiErroCode = 0 for qmiPort: rmnet_usb0 & userHandle: 486606848
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb1
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb2
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb3,
,I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb4
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb5
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb6
I/Atfwd_Daemon(  374): Received sys_event: 2 from QMI devId: rmnet_usb7
,I/ThermalEngine(  365): qmi: Instance id 157 for fusion TS,
,E/        (  357): csd_service_deinit: notifier handle release rc:0
,D/        (  357): csd_service_init: qmi_client_notifier_init() successful
,V/ImsSenderRxr( 1373): Read packet: 15 bytes
,V/ImsSenderRxr( 1373): processResponse
D/ImsSenderRxr( 1373): Response data: [12, 13, -1, -1, -1, -1, 16, 3, 24, -43, 1, 32, 0, 8, 0]
,D/ImsSenderRxr( 1373):  Tag -1 3 213 0
I/str_params(  357): key: 'all_call_states' value: ''
,I/str_params(  357): key: 'all_call_states' value: ''
I/str_params(  357): key: 'all_call_states' value: ''

```
