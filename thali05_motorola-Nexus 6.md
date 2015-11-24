#### Test 513350288bfb88c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3856): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3856): CheckJNI is OFF
D/AndroidRuntime( 3856): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{d262040 token=Token{3a5d1fc3 ActivityRecord{3d482f72 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  822): Adding window Window{31124635 u0 Starting com.test.thalitest} at 3 of 8 (after Window{18fed9a0 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1541): Closing mic
I/MicrophoneInputStream( 1541): mic_close com.google.android.apps.gsa.speech.audio.u@25332425
D/AndroidRuntime( 3856): Shutting down VM
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/ActivityManager(  822): Start proc 3870:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/HotwordRecognitionRnr( 1541): Stopping hotword detection.
I/HotwordRecognitionRnr( 1541): Hotword detection finished
I/ActivityManager(  822): Killing 3438:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3046:com.google.android.music:main/u0a66 (adj 15): empty #18
I/WebViewFactory( 3870): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3870): Time to load native libraries: 1 ms (timestamps 8806-8807)
I/LibraryLoader( 3870): Expected native library version number "",actual native library version number ""
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659520275
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
V/WebViewChromiumFactoryProvider( 3870): Binding Chromium to main looper Looper (main, tid 1) {237cdcd4}
I/LibraryLoader( 3870): Expected native library version number "",actual native library version number ""
I/chromium( 3870): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3870): Initializing chromium process, singleProcess=true
W/art     ( 3870): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3870): ApplicationContext is null in ApplicationStatus
W/chromium( 3870): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3870): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3870): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3870): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
I/kickstart(  877): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  877): STATUS: Wrote to /sys/power/wake_lock
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d6226a5:true
E/kickstart(  877): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  877): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
W/art     ( 3870): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3870): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3870): CordovaWebView is running on device made by: motorola
W/art     ( 3870): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3870): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3870): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3870): Validating map...
V/WindowManager(  822): Adding window Window{30630315 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{31124635 u0 Starting com.test.thalitest})
W/chromium( 3870): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3870): Initialized EGL, version 1.4
D/OpenGLRenderer( 3870): Enabling debug mode 0
I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +878ms (total +1m36s411ms)
I/Keyboard.Facilitator( 1251): onFinishInput()
W/BindingManager( 3870): Cannot call determinedVisibility() - never saw a connection for the pid: 3870
,D/JsMessageQueue( 3870): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3870): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576386944
D/JX-Cordova( 3870): jxcore cordova android initializing
,I/kickstart(  877): STATUS: Received file 'm9kefs2'
I/kickstart(  877): STATUS: 950272 bytes transferred in 0.996628 seconds
I/kickstart(  877): STATUS: Successfully downloaded files from target 
,I/kickstart(  877): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  877): STATUS: Sahara protocol completed
,W/jxcore-log( 3870): Initializing JXcore engine
W/jxcore-log( 3870): JXcore engine is ready
,W/jxcore-log( 3870): Starting JXcore engine
,W/.test.thalitest( 3870): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10577]" dev="sockfs" ino=10577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3870): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3870): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12708]" dev="sockfs" ino=12708 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3870): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22202]" dev="sockfs" ino=22202 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3870): Platform android
W/jxcore-log( 3870): 
W/jxcore-log( 3870): Process ARCH arm
W/jxcore-log( 3870): 
,I/jxcore-log( 3870): JXcore Cordova bridge is ready!
I/jxcore-log( 3870): 
W/jxcore-log( 3870): JXcore engine is started
,I/Choreographer( 3870): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3870): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3870): Toggling radios to true
I/jxcore-log( 3870): 
,D/BluetoothAdapter( 3870): enable(): BT is already enabled..!
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3870): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): my name is : motorola-Nexus 6_PT89
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): attempting to connect to test coordinator,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): check test folder,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): found test : ./testFindPeers.js
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): found test : ./testReConnect.js
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): found test : ./testSendData.js
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Test app app.js loaded
I/jxcore-log( 3870): 
,I/Choreographer( 3870): Skipped 115 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): BLE supported!!
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.13 rxSuccessRate=3.71 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,I/art     (  822): Explicit concurrent mark sweep GC freed 39682(1839KB) AllocSpace objects, 8(128KB) LOS objects, 32% free, 33MB/49MB, paused 2.219ms total 88.968ms
,D/Finsky  ( 3508): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3508): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3508): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.41 rxSuccessRate=1.98 targetRoamBSSID=any RSSI=-44
,E/WifiStateMachine(  822): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2462,5220
,V/GoogleAuthProtoRequest( 3083): [310] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3083): [311] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3083): [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3083): [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3083): [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3083): [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1274): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 38187(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.055ms total 30.617ms
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3508): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3508): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3508): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,E/Uploader( 1274): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1274): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1274): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1274): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
,E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
,E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
,E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	,... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38)
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 136706, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/Uploader( 1274): No account for auth token provided
,W/Uploader( 1274): No account for auth token provided
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/Uploader( 1274): No account for auth token provided
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (483 us),
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1274): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1274): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1274): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1274): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1274): No account for auth token provided
,W/Uploader( 1274): No account for auth token provided
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1274): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1274): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1274): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1274): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  822): Display changed displayId=0
,W/Uploader( 1274): No account for auth token provided
,W/Uploader( 1274): No account for auth token provided
,W/Uploader( 1274): No account for auth token provided
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  822): Excessive delay in setPowerMode(): 251ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,W/Uploader( 1274): No account for auth token provided
,E/WifiStateMachine(  822): cancelDelayedScan -> 11
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): cancelDelayedScan -> 13
,I/Keyboard.Facilitator( 1251): onFinishInput()
,E/native  (  822): do suspend true
,W/Uploader( 1274): No account for auth token provided
,W/Uploader( 1274): No account for auth token provided
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,W/Uploader( 1274):  no longer exists, so no auth token.
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1274): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1274): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
E/Uploader( 1274): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
,E/Uploader( 1274): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.c(SourceFile:550),
E/Uploader( 1274): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1274): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1274): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1274): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1274): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1274): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1274): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1274): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3870): 
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
,E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3508): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3508): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3508): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  822): Explicit concurrent mark sweep GC freed 42715(2MB) AllocSpace objects, 12(380KB) LOS objects, 31% free, 34MB/50MB, paused 1.716ms total 89.826ms
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1848): Handling authorization failure
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
,V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163918, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 166020, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1251): run()
I/Keyboard.Facilitator( 1251): flushDynamicLanguageModels()
,I/ConfigService( 1274): onCreate
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/ConfigService( 1274): onDestroy
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38)
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 227878, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Coordinator is now connected to the server!,
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 70048(4MB) AllocSpace objects, 8(728KB) LOS objects, 36% free, 28MB/44MB, paused 1.647ms total 66.843ms
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
,E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3792): Sync error,
,E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3792): Finished books sync,
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 313730, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Start proc 3999:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 3999): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 3999):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3999):   adb logcat -s GAv4
,W/GAv4    ( 3999): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3999): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3999): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 3548:com.google.android.gms:car/u0a11 (adj 15): empty #17
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1848): Handling authorization failure
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
,V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 318719, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3083): [312] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3083): [313] a.<init>: mAccountName set to: thalitester@gmail.com
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@14f65c8a}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3083): [313] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3083): [313] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3083): [312] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3083): [312] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  822): Explicit concurrent mark sweep GC freed 37518(1613KB) AllocSpace objects, 10(631KB) LOS objects, 31% free, 34MB/50MB, paused 1.392ms total 70.579ms
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@14f65c8a}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1274): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1274): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
W/GLSActivity( 1274): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
,W/GLSActivity( 1274): 	,at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1274): 	,at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1274): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
,W/GLSActivity( 1274): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3508): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3508): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3508): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3508): ,	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3508): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3508): ,	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3508): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3508): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/jxcore-log( 3870): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector command called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":14,"addressList":[{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0}]}
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Start now : testSendData.js,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): stop tests now !,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 14
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): check server
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): serverPort is 54438
,I/jxcore-log( 3870): 
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/        ( 3870): Stoping All
,I/        ( 3870): Stopping services
I/        ( 3870): Stop Bluetooth
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3870): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3870):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"},
,D/WifiService(  822): New client listening to asynchronous messages,
,I/        ( 3870): All stuff available and enabled
I/        ( 3870): Stoping All
,I/        ( 3870): Stopping services,
I/        ( 3870): Stop Bluetooth
I/        ( 3870): Starting All,
I/        ( 3870): Stopping services
I/        ( 3870): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@35a07d5e
,I/        ( 3870): Stopping services
I/        ( 3870): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}
I/        ( 3870): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, length : 80
I/        ( 3870): peerDiscoveryTimer timeout value:8249
,I/        ( 3870): Stop Bluetooth,
I/        ( 3870): StartBluetooth listener
,I/        ( 3870): StartBluetooth listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3870): StartBroadcasting started ok
,I/jxcore-log( 3870): 
,I/BTListenerThread( 3870): starting to listen
,I/BTListenerThread( 3870): waiting to accept incoming Connection,
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: E0:DB:10:14:E2:C0,
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): 2015-11-24T12:31:12.115Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:12.116Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:12.116Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: E0:DB:10:14:E2:C0, name: null
I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at E0:DB:10:14:E2:C0
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3870): 2015-11-24T12:31:12.126Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined,
I/jxcore-log( 3870): 
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 3870): We already were running, thus doing nothing
I/        ( 3870): Added local service
I/        ( 3870): Cleared service requests
I/        ( 3870): Stopped peer discovery
,I/        ( 3870): Started peer discovery
I/        ( 3870): Discovery state changed to Started.
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,D/btif_config( 2201): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/ActivityManager(  822): Start proc 4046:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13bef3d5:true
,I/ActivityManager(  822): Killing 2509:com.google.android.calendar/u0a37 (adj 15): empty #17
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 1 peers.
,I/SS      ( 3870): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,I/        ( 3870): Started service discovery
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f90eb4 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/btif_config( 2201): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 2201): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6999","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3870): HandshakeOk : samsung-SM-N910C_PT6999
I/HS      ( 3870): Hand Shake finished outgoing for : samsung-SM-N910C_PT6999
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, samsung-SM-N910C_PT6999
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 44101
,I/BtConnectorHelper( 3870): Request socket is using : 44101
I/BtToRequestSocket( 3870): Now accepting connections
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3870): we got incoming connection
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread,
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 79 bytes.
,I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT283
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, HTC-HTC One_M8_PT283
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438,
,I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:31:21.660Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :44101
,I/jxcore-log( 3870): 2015-11-24T12:31:21.706Z SendDataConnector.js: CLIENT connected to 44101, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:21.707Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 44101
,I/BtToRequestSocket( 3870): Set local streams
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,I/jxcore-log( 3870): 2015-11-24T12:31:21.721Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:539
,I/jxcore-log( 3870): 2015-11-24T12:31:22.066Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.134Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.191Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.197Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.208Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.212Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.215Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.219Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.229Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.262Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.274Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.279Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.283Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.289Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.292Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.322Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.332Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.336Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.340Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:31:22.363Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.402Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.407Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.425Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.442Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.496Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.537Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.592Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.600Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.614Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:31:22.620Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.652Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.662Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.668Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.677Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.685Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.687Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.721Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.722Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:22.731Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.731Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: E0:DB:10:14:E2:C0
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3870): 2015-11-24T12:31:22.743Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3870): 
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:22.745Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:22.745Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:22.745Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 80:01:84:8A:B3:68, name: null
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 80:01:84:8A:B3:68
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 10609 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63),
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3870): 2015-11-24T12:31:22.762Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3870): 2015-11-24T12:31:22.880Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.979Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:31:22.985Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.992Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:22.998Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.033Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.046Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.083Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.111Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.126Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.132Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): No ag scb for peer addr
,I/jxcore-log( 3870): 2015-11-24T12:31:23.155Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:23.192Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	,at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	,at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): ,	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	,at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
,E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): ,	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): ,	... 14 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
,E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143),
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): ,	at czr.a(PG:65),
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): ,	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	,at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	,at fal.a(PG:38)
,E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 383334, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6999","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6999","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6999, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6999, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91244 rs_disc_pending=1,
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:,
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77,
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,W/bt-btif ( 2201): invalid rfc slot id: 4
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT283
I/BtToSocketBase( 3870): Stop ReceivingThread
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT283
I/BtToSocketBase( 3870): Close bt socket
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out,
I/BtToSocketBase( 3870): Close bt socket
,I/jxcore-log( 3870): 2015-11-24T12:31:23.937Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,D/btif_config( 2201): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 80:01:84:8A:B3:68,
I/BluetoothBondStateMachine( 2201): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive,
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b83eefd:true
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x43
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9107c rs_disc_pending=0
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC One_M8
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,D/btif_config( 2201): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3870): we got incoming connection
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started,
,I/BTListenerThread( 3870): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9717","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
,I/HS      ( 3870): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT9717
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT9717
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BTConnectedThread,
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.,
I/BtToRequestSocket( 3870): --DoOneRunRound started,
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:31:38.119Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.676Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.700Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.704Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.711Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.715Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.746Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:31:38.784Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.822Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.831Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.835Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.850Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:31:38.882Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.888Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.939Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.955Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:38.959Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.033Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.072Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.081Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.112Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.129Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.137Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.177Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.183Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.188Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.232Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.314Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.319Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.329Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.506Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.612Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.627Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.632Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.667Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.716Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.752Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.764Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.779Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.826Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.869Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.874Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:31:39.878Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 6,
I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT9717
I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3870): 2015-11-24T12:31:39.935Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9140c rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: ALE-L21
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 3 peers.
I/SS      ( 3870): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3870): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-rfcomm( 2201): PORT_StartCnf failed result:5
E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2201): invalid rfc slot id: 7
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothMapService( 2201): onReceive
,I/jxcore-log( 3870): 2015-11-24T12:31:55.301Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:55.302Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:31:55.303Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC Desire 820
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery,
,I/jxcore-log( 3870): 2015-11-24T12:32:00.305Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:00.306Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:05.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:05.312Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:05.313Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:05.314Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68,
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): No ag scb for peer addr
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [80:01:84:8a:b3:68]: 6, 10f, 608
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC Desire 820,
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3870): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : HTC-HTC Desire 820_PT7085
I/HS      ( 3870): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT7085
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT7085
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 45037
I/BtConnectorHelper( 3870): Request socket is using : 45037
,I/BtToRequestSocket( 3870): Now accepting connections
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255,
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3870): we got incoming connection
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :45037
,I/jxcore-log( 3870): 2015-11-24T12:32:10.334Z SendDataConnector.js: CLIENT connected to 45037, error: null,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:10.335Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 45037
,I/BtToRequestSocket( 3870): Set local streams
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,I/jxcore-log( 3870): 2015-11-24T12:32:10.348Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): ,
I/BTListenerThread( 3870): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3870): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT7085
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT7085
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:32:10.396Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:10.648Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:10.765Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:32:10.855Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:10.868Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:10.930Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.098Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.109Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.235Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.287Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.323Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.389Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.400Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.405Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.411Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.522Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:11.600Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.231Z SendDataConnector.js: CLIENT is data received : 70000
,I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3870): 2015-11-24T12:32:12.342Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.416Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.492Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.506Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.542Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.578Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.586Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.591Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.592Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:12.596Z SendDataConnector.js: CLIENT Stop now
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.598Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3870): Stop ReceivingThread
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
,I/jxcore-log( 3870): 2015-11-24T12:32:12.611Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.613Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:12.614Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:12.614Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 49848 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3870): 2015-11-24T12:32:12.628Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.633Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.755Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:32:12.763Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.801Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91244 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3870): 2015-11-24T12:32:12.981Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:12.988Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91244 rs_disc_pending=0
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 3870): 2015-11-24T12:32:14.142Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.151Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.182Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.205Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.242Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.248Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.281Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.289Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.295Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.546Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.770Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:14.852Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:15.056Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:15.221Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:15.307Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:15.459Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:15.557Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data,
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 3 peers.
I/SS      ( 3870): Peer(1): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3870): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3870): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/jxcore-log( 3870): 2015-11-24T12:32:15.723Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:15.866Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:16.005Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:16.137Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:16.297Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:16.368Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 8
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT7085
I/BtToSocketBase( 3870): Stop ReceivingThread
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt in
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Close bt out
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT7085
I/BtToSocketBase( 3870): Close bt socket
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/jxcore-log( 3870): 2015-11-24T12:32:16.579Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,I/        ( 3870): Started service discovery
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 11
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:32:18.103Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:18.104Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:18.105Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC Desire 820
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8827, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8827, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3870): 2015-11-24T12:32:23.107Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:23.107Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7101","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7101","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7101, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7101, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3870): 2015-11-24T12:32:28.111Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:28.112Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:28.112Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:28.113Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: ALE-L21
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6999","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6999","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT6999, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT6999, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9717","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : HUAWEI-ALE-L21_PT9717
I/HS      ( 3870): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT9717
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT9717
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 39585
,I/BtConnectorHelper( 3870): Request socket is using : 39585
I/BtToRequestSocket( 3870): Now accepting connections
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :39585
,I/jxcore-log( 3870): 2015-11-24T12:32:31.842Z SendDataConnector.js: CLIENT connected to 39585, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:31.843Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 39585
I/BtToRequestSocket( 3870): Set local streams
,I/jxcore-log( 3870): 2015-11-24T12:32:31.850Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:408
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3870): 2015-11-24T12:32:32.364Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3870): 2015-11-24T12:32:32.520Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:32.908Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3870): 2015-11-24T12:32:33.117Z SendDataConnector.js: CLIENT is data received : 40000
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:33.449Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:33.708Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:33.942Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.072Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.304Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.459Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.460Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.467Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.469Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: 58:2A:F7:ED:96:BE,
I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in,
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
,I/jxcore-log( 3870): 2015-11-24T12:32:34.477Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:34.483Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:34.483Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:34.484Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3870): Connecting to null, at 44:80:EB:7B:5A:05
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 21848 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9140c rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3,
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,D/btif_config( 2201): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3870): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : motorola-XT1072_PT4007
,I/HS      ( 3870): Hand Shake finished outgoing for : motorola-XT1072_PT4007
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, motorola-XT1072_PT4007
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 41463
I/BtConnectorHelper( 3870): Request socket is using : 41463
,I/BtToRequestSocket( 3870): Now accepting connections
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :41463
,I/jxcore-log( 3870): 2015-11-24T12:32:40.735Z SendDataConnector.js: CLIENT connected to 41463, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:40.736Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 41463
,I/BtToRequestSocket( 3870): Set local streams
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,I/jxcore-log( 3870): 2015-11-24T12:32:40.747Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4504
,I/jxcore-log( 3870): 2015-11-24T12:32:40.976Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3870): 2015-11-24T12:32:41.370Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.390Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8149
,I/jxcore-log( 3870): 2015-11-24T12:32:41.432Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.443Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.506Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.516Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.655Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.663Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.771Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.772Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.777Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:41.778Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
I/BtConnectorHelper( 3870): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3870): Stop ReceivingThread
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): 2015-11-24T12:32:41.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:41.786Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:32:41.787Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:32:41.787Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: 7C:F9:0E:37:96:AB, name: null
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/        ( 3870): Connecting to null, at 7C:F9:0E:37:96:AB
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 7289 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f915d4 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 4 peers.
I/SS      ( 3870): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(2): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3870): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3870): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive,
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1541): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Started service discovery
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 6 peers.,
I/SS      ( 3870): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
,I/SS      ( 3870): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3870): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x44,
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 14
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:33:16.275Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:16.276Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:16.276Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:21.277Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:21.278Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 7 peers.
I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3870): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/jxcore-log( 3870): 2015-11-24T12:33:26.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:26.282Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:26.283Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:26.284Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3870): Connecting to null, at 7C:F9:0E:37:96:AB
I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Note4-1
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3870): we got incoming connection
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6999","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
,I/HS      ( 3870): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT6999
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, samsung-SM-N910C_PT6999,
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:33:29.510Z SendDataTCPServer.js: TCP/IP server connected,
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:29.989Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.054Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.122Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.186Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.254Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.320Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.385Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.456Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.526Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.530Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3870): 2015-11-24T12:33:30.600Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.666Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.713Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.725Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.741Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.753Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.759Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:33:30.794Z SendDataTCPServer.js: TCP/IP server has received 42940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.802Z SendDataTCPServer.js: TCP/IP server has received 44920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.807Z SendDataTCPServer.js: TCP/IP server has received 46900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:30.841Z SendDataTCPServer.js: TCP/IP server has received 48880 bytes of data
I/jxcore-log( 3870): 
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f90eb4 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3870): 2015-11-24T12:33:31.013Z SendDataTCPServer.js: TCP/IP server has received 50860 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.019Z SendDataTCPServer.js: TCP/IP server has received 52840 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.051Z SendDataTCPServer.js: TCP/IP server has received 62740 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.059Z SendDataTCPServer.js: TCP/IP server has received 64720 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.092Z SendDataTCPServer.js: TCP/IP server has received 68680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.097Z SendDataTCPServer.js: TCP/IP server has received 70660 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.102Z SendDataTCPServer.js: TCP/IP server has received 72640 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.132Z SendDataTCPServer.js: TCP/IP server has received 78580 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.176Z SendDataTCPServer.js: TCP/IP server has received 80560 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.182Z SendDataTCPServer.js: TCP/IP server has received 82540 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.212Z SendDataTCPServer.js: TCP/IP server has received 90460 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.222Z SendDataTCPServer.js: TCP/IP server has received 92440 bytes of data
I/jxcore-log( 3870): 
,D/btif_config( 2201): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/jxcore-log( 3870): 2015-11-24T12:33:31.252Z SendDataTCPServer.js: TCP/IP server has received 96400 bytes of data
I/jxcore-log( 3870): 
I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/jxcore-log( 3870): 2015-11-24T12:33:31.266Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 10
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT6999
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
I/jxcore-log( 3870): 2015-11-24T12:33:31.337Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3870): HandshakeOk : samsung-SM-A500FU_PT8827
I/HS      ( 3870): Hand Shake finished outgoing for : samsung-SM-A500FU_PT8827
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, samsung-SM-A500FU_PT8827
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 49414
,I/BtConnectorHelper( 3870): Request socket is using : 49414
I/BtToRequestSocket( 3870): Now accepting connections
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f90eb4 rs_disc_pending=0
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x49
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :49414
,I/jxcore-log( 3870): 2015-11-24T12:33:31.819Z SendDataConnector.js: CLIENT connected to 49414, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:31.820Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 49414,
I/BtToRequestSocket( 3870): Set local streams
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,I/jxcore-log( 3870): 2015-11-24T12:33:31.833Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3870): 2015-11-24T12:33:32.034Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.108Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3870): 2015-11-24T12:33:32.132Z SendDataConnector.js: CLIENT is data received : 30000
,I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5179
,I/jxcore-log( 3870): 2015-11-24T12:33:32.180Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.225Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.230Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.288Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.297Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.345Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.391Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:32.391Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.395Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:32.396Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3870): 2015-11-24T12:33:32.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:32.404Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:32.405Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:32.406Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/        ( 3870): Selected device address: 7C:F9:0E:34:8A:A0, name: null
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 7C:F9:0E:34:8A:A0
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 50606 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f90eb4 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91964 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Note4-1
,D/btif_config( 2201): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1,
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1541): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91964 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : samsung-SM-G900F_PT7562
I/HS      ( 3870): Hand Shake finished outgoing for : samsung-SM-G900F_PT7562
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, samsung-SM-G900F_PT7562
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3870): mHTTPPort  set to : 50450
I/BtConnectorHelper( 3870): Request socket is using : 50450
I/BtToRequestSocket( 3870): Now accepting connections
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :50450
,I/jxcore-log( 3870): 2015-11-24T12:33:37.905Z SendDataConnector.js: CLIENT connected to 50450, error: null
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:37.905Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 50450,
I/BtToRequestSocket( 3870): Set local streams
I/jxcore-log( 3870): 2015-11-24T12:33:37.913Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): rin ended ---------------------------;
,I/jxcore-log( 3870): 2015-11-24T12:33:38.371Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.426Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.486Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.499Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.580Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.599Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.675Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.743Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:38.836Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:39.357Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:39.357Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:39.362Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:39.363Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Close LocalOutputStream
,I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in,
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket,
,I/BtToRequestSocket( 3870): Close server socket,
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): 2015-11-24T12:33:39.372Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:39.375Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:39.375Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:39.376Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: E0:DB:10:1F:C9:5E, name: null
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at E0:DB:10:1F:C9:5E
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 6953 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND,
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91964 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,D/btif_config( 2201): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : samsung-SM-N9005_PT8756
I/HS      ( 3870): Hand Shake finished outgoing for : samsung-SM-N9005_PT8756
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, samsung-SM-N9005_PT8756
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 60623
,I/BtConnectorHelper( 3870): Request socket is using : 60623
I/BtToRequestSocket( 3870): Now accepting connections
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :60623
,I/jxcore-log( 3870): 2015-11-24T12:33:41.211Z SendDataConnector.js: CLIENT connected to 60623, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.212Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 60623
I/BtToRequestSocket( 3870): Set local streams
I/jxcore-log( 3870): 2015-11-24T12:33:41.219Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 3870): 2015-11-24T12:33:41.390Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.441Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.492Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.551Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.580Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.678Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.684Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.745Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.836Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.899Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.900Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:41.907Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:41.908Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
I/jxcore-log( 3870): 2015-11-24T12:33:41.927Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:41.936Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:41.938Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
,I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:41.938Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 2525 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive,
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: S5-1,
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3870): Peer(5): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Started service discovery
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Note3-1
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,D/btif_config( 2201): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1,
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0,
D/BluetoothAdapterProperties( 2201): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTConnectToThread( 3870): got MESSAGE_READ 83 bytes.,
I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : samsung-SM-A300FU_PT6406
,I/HS      ( 3870): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6406
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6406
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3870): mHTTPPort  set to : 41760
,I/BtConnectorHelper( 3870): Request socket is using : 41760
I/BtToRequestSocket( 3870): Now accepting connections
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :41760
,I/jxcore-log( 3870): 2015-11-24T12:33:49.652Z SendDataConnector.js: CLIENT connected to 41760, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:49.653Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 41760
,I/BtToRequestSocket( 3870): Set local streams
I/jxcore-log( 3870): 2015-11-24T12:33:49.661Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,I/jxcore-log( 3870): 2015-11-24T12:33:49.778Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:49.846Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,I/jxcore-log( 3870): 2015-11-24T12:33:49.892Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:49.899Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3063
,I/jxcore-log( 3870): 2015-11-24T12:33:49.935Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.002Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.047Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.051Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.082Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.138Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.139Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.143Z SendDataConnector.js: CLIENT Stop now
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.143Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3870): 
I/BtConnectorHelper( 3870): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream,
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
,I/jxcore-log( 3870): 2015-11-24T12:33:50.151Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:50.153Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:33:50.154Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:33:50.155Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null,
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 8203 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 556061, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9595","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9595","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT9595, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT9595, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/SS      ( 3870): Found 4 peers.
I/SS      ( 3870): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3870): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 20
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:34:22.482Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:22.483Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:22.484Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,V/GoogleAuthProtoRequest( 3083): [314] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3083): [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3083): [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3083): [315] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3083): [315] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3083): [315] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3870): 2015-11-24T12:34:27.486Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:27.487Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:32.491Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:32.492Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:34:32.492Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:32.493Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x10  CID 0x41
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 21
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:34:37.881Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:34:37.881Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:37.882Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:42.883Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:34:42.884Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: XT1072
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3870): we got incoming connection
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3870): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
,I/HS      ( 3870): Incoming connection Hand Shake finished for : motorola-XT1072_PT4007
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, motorola-XT1072_PT4007
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
,I/jxcore-log( 3870): 2015-11-24T12:34:45.620Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:34:46.046Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.052Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.059Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.064Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.067Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.074Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.088Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.149Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.154Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.165Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.171Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.174Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.182Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.212Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.225Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.239Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.271Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.336Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.349Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.369Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.403Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.408Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.424Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.463Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.492Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.527Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.547Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.553Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.592Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.606Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.642Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:34:46.691Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.732Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.739Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.772Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:46.813Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 16
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT4007,
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
,I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
,I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Close bt out
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt socket
,I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT4007
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
,I/jxcore-log( 3870): 2015-11-24T12:34:46.877Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3870): 2015-11-24T12:34:47.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:34:47.889Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:34:47.890Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:34:47.890Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null,
,I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f915d4 rs_disc_pending=1
E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: XT1072
,I/art     (  822): Explicit concurrent mark sweep GC freed 42329(2001KB) AllocSpace objects, 11(553KB) LOS objects, 31% free, 34MB/50MB, paused 2.477ms total 90.170ms
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1848): Handling authorization failure
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
,V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 55503(2MB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 27MB/43MB, paused 1.955ms total 71.994ms
,E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
,W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 595952, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92084 rs_disc_pending=0
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/btif_config( 2201): btif_get_device_type: Device [90:e7:c4:f6:69:77] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1,
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
D/BluetoothAdapterProperties( 2201): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State,
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3870): we got incoming connection
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3870): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : HTC-HTC One M8s_PT9674
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, HTC-HTC One M8s_PT9674
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3870): --DoOneRunRound started,
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438,
,I/BtToRequestSocket( 3870): --DoOneRunRound ended
I/jxcore-log( 3870): 2015-11-24T12:35:01.819Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.244Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.300Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.319Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.374Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.384Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.404Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.444Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.483Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.491Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.502Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.543Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.547Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.587Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:35:02.622Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.630Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.643Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.675Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.712Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.746Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.756Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.763Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.775Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.813Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.837Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.878Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.885Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.922Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.931Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.938Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.972Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.976Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:02.983Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:03.026Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:03.062Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:03.103Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:03.109Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:03.143Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 22
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One M8s_PT9674
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
,I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
,I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt socket
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One M8s_PT9674
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/jxcore-log( 3870): 2015-11-24T12:35:03.189Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/SS      ( 3870): We got empty peers list
,I/SS      ( 3870): We got empty peers list
I/SS      ( 3870): We got empty peers list
I/SS      ( 3870): We got empty peers list
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/SS      ( 3870): Found 1 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91964 rs_disc_pending=0
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 23
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:35:21.573Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:21.574Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:21.575Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3870): we got incoming connection
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/BTListenerThread( 3870): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT7562
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, samsung-SM-G900F_PT7562
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
,I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:35:22.721Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.328Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.516Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.617Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.632Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.676Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.684Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:35:23.732Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.772Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.791Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.849Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.857Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.871Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.900Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:35:23.932Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:23.998Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.032Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.036Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.039Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.046Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.130Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.133Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.139Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.143Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.162Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.202Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.265Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.269Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.316Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.319Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.368Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.402Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.489Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.584Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.587Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.638Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.759Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.821Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.825Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.884Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.889Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.981Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.984Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:24.989Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:25.038Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:25.044Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:25.072Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:25.103Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:25.110Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 24
I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT7562
I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
,I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt socket
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT7562
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/jxcore-log( 3870): 2015-11-24T12:35:25.281Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 3870): 2015-11-24T12:35:26.577Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:26.578Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: S5-1
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/jxcore-log( 3870): 2015-11-24T12:35:31.582Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:31.583Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:31.584Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:31.584Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x10  CID 0x46
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 26
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:35:37.895Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:37.896Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:37.897Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 3 peers.
,I/SS      ( 3870): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3870): 2015-11-24T12:35:42.898Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): 2015-11-24T12:35:42.899Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8827, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8827, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:,
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3870): 2015-11-24T12:35:47.902Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:35:47.903Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:47.904Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:35:47.904Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
,E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38)
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089),
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 664868, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery,
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 6 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3870): we got incoming connection
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
,I/HS      ( 3870): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6406
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6406
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): Creating BTConnectedThread
,I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
,I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:36:15.667Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 7 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Note4-1 92:b6:86:43:73:1c,
I/SS      ( 3870): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3870): Added service request
,I/jxcore-log( 3870): 2015-11-24T12:36:16.191Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.222Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.326Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.386Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.450Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.468Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.482Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.523Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.557Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.564Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.608Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.675Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.700Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.758Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:36:16.811Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.830Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.888Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:16.979Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.063Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.069Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.076Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.159Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.217Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.338Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.345Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.374Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.412Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.430Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.440Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.597Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:36:17.667Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.702Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.732Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.739Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.771Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.778Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.787Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.822Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3870): 2015-11-24T12:36:17.863Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.888Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.893Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.925Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.981Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.992Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:17.999Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:18.041Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 2201): invalid rfc slot id: 25
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6406
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt socket
,I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6406
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/jxcore-log( 3870): 2015-11-24T12:36:18.207Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 27
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:36:18.563Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:18.564Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:18.569Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:18.572Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): 2015-11-24T12:36:18.575Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:18.576Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:18.577Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 148411 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91cf4 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 29
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:36:20.614Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:20.614Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:20.615Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91cf4 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:36:25.617Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:25.618Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: A5-1
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3870): we got incoming connection
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/BTListenerThread( 3870): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT8827
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, samsung-SM-A500FU_PT8827
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
,I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:36:28.830Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.248Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.257Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.263Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.279Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.336Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.342Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.348Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.382Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.418Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.426Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.437Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.471Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.512Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.518Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.524Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.562Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.598Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.607Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.619Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.652Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.685Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.695Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.702Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.709Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.767Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.778Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.784Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.796Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.864Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.902Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.942Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.950Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.956Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:29.962Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.002Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.044Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.053Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:36:30.125Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:36:30.162Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.213Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.221Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.261Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.303Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.309Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 28
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT8827,
I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt in
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT8827
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/jxcore-log( 3870): 2015-11-24T12:36:30.405Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 3870): 2015-11-24T12:36:30.622Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:30.623Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:30.623Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:30.624Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9179c rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 31
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:36:32.918Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:32.919Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:32.919Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9179c rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: A5-1
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 8 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3870): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:36:37.920Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:37.921Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:42.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:42.929Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:42.930Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:42.930Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null,
,I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 32
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:36:45.295Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:45.295Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:45.297Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:36:50.298Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:50.299Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:55.304Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:55.304Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:55.305Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:55.305Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null,
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 33
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:36:56.138Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:36:56.139Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:36:56.139Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:37:01.142Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:01.144Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3870): 2015-11-24T12:37:06.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:06.151Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:06.152Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:06.152Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10,
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109,
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 34,
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:37:06.963Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:06.964Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:06.968Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:06.971Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
,I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:06.978Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:06.979Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:06.980Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 48389 ms, rnd: 5, ex: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9224c rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL,
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x44,
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 35
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:37:12.303Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:12.304Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:12.305Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/SS      ( 3870): Found 3 peers.
I/SS      ( 3870): Peer(1): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3870): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:37:17.306Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:17.307Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3870): 2015-11-24T12:37:22.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:22.312Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:22.313Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:22.313Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x1f  CID 0x48
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 36
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:37:25.358Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:25.359Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:25.360Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8827, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8827, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3870): 2015-11-24T12:37:30.362Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:30.362Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3870): 2015-11-24T12:37:35.365Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:35.366Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:35.367Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:37:35.367Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 37
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:37:36.445Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:36.446Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:36.446Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Cleared service requests
I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started peer discovery
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 6 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3870): 2015-11-24T12:37:41.448Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:41.448Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/jxcore-log( 3870): 2015-11-24T12:37:46.452Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:46.453Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:46.453Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:46.453Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2201): invalid rfc slot id: 38
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:37:51.606Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:51.607Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:51.608Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:56.609Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:37:56.610Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:01.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:01.615Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:01.615Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:01.616Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null,
,I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41,
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 39
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:38:04.844Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:04.845Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:04.853Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:04.856Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:04.861Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:04.861Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:04.861Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/        ( 3870): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 57868 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92414 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92414 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x1f  CID 0x46
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 40
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:38:09.247Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:09.249Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:09.251Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:14.252Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:14.253Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3870): we got incoming connection
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT8756
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, samsung-SM-N9005_PT8756
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BTConnectedThread
,I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438
I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:38:14.923Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.295Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:38:15.367Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.375Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.395Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.402Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.408Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.442Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.471Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.502Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.509Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.514Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.569Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.576Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.581Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.586Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.596Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.601Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.633Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.672Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.712Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.724Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.762Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.770Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.777Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:15.813Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,W/bt-btif ( 2201): invalid rfc slot id: 30
,I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT8756
I/BtToSocketBase( 3870): Stop ReceivingThread
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
,I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT8756
,I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/jxcore-log( 3870): 2015-11-24T12:38:15.879Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x47
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3870): 2015-11-24T12:38:19.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:19.258Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:19.258Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:19.259Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f91b2c rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [90:e7:c4:f6:69:77]: 7, f, 6109,
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC One M8s
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3870): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3870): HandshakeOk : HTC-HTC One M8s_PT9674
,I/HS      ( 3870): Hand Shake finished outgoing for : HTC-HTC One M8s_PT9674
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, HTC-HTC One M8s_PT9674
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 57847,
I/BtConnectorHelper( 3870): Request socket is using : 57847
,I/BtToRequestSocket( 3870): Now accepting connections
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :57847
,I/jxcore-log( 3870): 2015-11-24T12:38:21.915Z SendDataConnector.js: CLIENT connected to 57847, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:21.916Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 57847
,I/BtToRequestSocket( 3870): Set local streams
I/jxcore-log( 3870): 2015-11-24T12:38:21.924Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3870): 2015-11-24T12:38:22.102Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3870): 2015-11-24T12:38:22.180Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11119
,I/jxcore-log( 3870): 2015-11-24T12:38:22.244Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.252Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3870): 2015-11-24T12:38:22.325Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.331Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.379Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.465Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.471Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.503Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.504Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.511Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.512Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
I/BtConnectorHelper( 3870): Disconnect outgoing peer: 90:E7:C4:F6:69:77
I/BtToSocketBase( 3870): Stop ReceivingThread
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
,I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3870): Close bt out
I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): 2015-11-24T12:38:22.519Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:22.522Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:22.522Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:22.523Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8,
I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 17643 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92084 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [50:2e:6c:ac:21:50]: 7, f, 6109
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92084 rs_disc_pending=1,
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9107c rs_disc_pending=1,
,W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3870): Starting to Handshake
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9107c rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3870): got MESSAGE_READ 79 bytes.
I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3870): HandshakeOk : HTC-HTC One_M8_PT283
I/HS      ( 3870): Hand Shake finished outgoing for : HTC-HTC One_M8_PT283
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, HTC-HTC One_M8_PT283
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 41019
,I/BtConnectorHelper( 3870): Request socket is using : 41019
I/BtToRequestSocket( 3870): Now accepting connections
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :41019
,I/jxcore-log( 3870): 2015-11-24T12:38:27.378Z SendDataConnector.js: CLIENT connected to 41019, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.381Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.392Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,I/jxcore-log( 3870): 
I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 41019
I/BtToRequestSocket( 3870): Set local streams,
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3870): 2015-11-24T12:38:27.568Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17059,
,I/jxcore-log( 3870): 2015-11-24T12:38:27.618Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12109
,I/jxcore-log( 3870): 2015-11-24T12:38:27.630Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5179
,I/jxcore-log( 3870): 2015-11-24T12:38:27.670Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.677Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.709Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.757Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.802Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.807Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.808Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.811Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:27.811Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
I/BtConnectorHelper( 3870): Disconnect outgoing peer: 50:2E:6C:AC:21:50
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
,I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
,I/BtToRequestSocket( 3870): Close server socket
I/jxcore-log( 3870): 2015-11-24T12:38:27.816Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:27.818Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:27.819Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): 2015-11-24T12:38:27.820Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/        ( 3870): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3870): Starting to connect
I/        ( 3870): Connecting to null, at 34:FC:EF:11:AE:67
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 5286 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f9107c rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: HTC One_M8
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 5 peers.
I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3870): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d,
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request,
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 44
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:38:59.161Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:38:59.162Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:38:59.163Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3870): 2015-11-24T12:39:04.164Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:04.165Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:09.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:39:09.170Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:09.170Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:39:09.171Z SendDataConnector.js: do connect now,
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 34:FC:EF:11:AE:67
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x9  CID 0x41
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 45
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:39:10.033Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:39:10.035Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:10.035Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:15.036Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:15.037Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3870): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3870): 2015-11-24T12:39:20.042Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:20.042Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:39:20.043Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:39:20.044Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 34:FC:EF:11:AE:67
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 46
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:39:52.580Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:39:52.581Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:39:52.581Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3870): 2015-11-24T12:39:57.582Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:39:57.583Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/jxcore-log( 3870): 2015-11-24T12:40:02.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:02.588Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:02.589Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:02.589Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 3870): Connecting to null, at 34:FC:EF:11:AE:67,
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): No ag scb for peer addr
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 7 peers.,
I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3870): Found 7 peers.
I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/wpa_supplicant( 1134): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 8 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3870): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/        ( 3870): Started service discovery
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config( 2201): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3870): we got incoming connection
,I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread,
I/BTListenerThread( 3870): waiting to accept incoming Connection
W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3870): Starting to Handshake,
I/BTHandshakeSocketThread( 3870): Creating BTHandshakeSocketThread
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
I/BTConnectToThread( 3870): MESSAGE_WRITE 80 bytes.
,I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread started
,I/BTListenerThread( 3870): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3870): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTListenerThread( 3870): MESSAGE_WRITE 80 bytes.
I/HS      ( 3870): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT6814
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped,
I/BtConnectorHelper( 3870): Starting the connected thread incoming : true, LGE-Nexus 5_PT6814,
I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BTConnectedThread
I/BtConnectorHelper( 3870): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3870): --DoOneRunRound started
,I/BtToRequestSocket( 3870): LocalHost address: localhost/127.0.0.1, port: 54438,
I/BtToRequestSocket( 3870): --DoOneRunRound ended
,I/jxcore-log( 3870): 2015-11-24T12:40:50.351Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3870): 
,I/BTConnectToThread( 3870): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3870): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3870): HandshakeOk : LGE-Nexus 5_PT6814
I/HS      ( 3870): Hand Shake finished outgoing for : LGE-Nexus 5_PT6814
I/BTHandshakeSocketThread( 3870): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3870): Starting the connected thread incoming : false, LGE-Nexus 5_PT6814
,I/BtToSocketBase( 3870): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3870): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3870): mHTTPPort  set to : 54343
I/BtConnectorHelper( 3870): Request socket is using : 54343
,I/BtToRequestSocket( 3870): Now accepting connections
,I/BtConnectorHelper( 3870): Calling ConnectionStatusUpdate with port :54343
,I/jxcore-log( 3870): 2015-11-24T12:40:50.670Z SendDataConnector.js: CLIENT connected to 54343, error: null
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.671Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3870): 
,I/BtToRequestSocket( 3870): incoming data from: /127.0.0.1, port: 54343
I/BtToRequestSocket( 3870): Set local streams
,I/jxcore-log( 3870): 2015-11-24T12:40:50.682Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3870): 
I/BtToRequestSocket( 3870): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29929
,I/jxcore-log( 3870): 2015-11-24T12:40:50.777Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.791Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3870): 
,D/GCM     ( 1274): Message class com.google.f.a.a.i
,I/jxcore-log( 3870): 2015-11-24T12:40:50.817Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.823Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.830Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.837Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.875Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.919Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.926Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.958Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.973Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.981Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:50.998Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.033Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.037Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.043Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3870): 2015-11-24T12:40:51.050Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.056Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.093Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.132Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.137Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.148Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:51.152Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.169Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.202Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3870): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3870): 2015-11-24T12:40:51.229Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.269Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.302Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.311Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.317Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.324Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.363Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.367Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.371Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.395Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:51.399Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.413Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.492Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.494Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:51.497Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.541Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.572Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
,I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.579Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.585Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.592Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:51.596Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.672Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.712Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.720Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:51.724Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.728Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.746Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.841Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.842Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.847Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.848Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3870): 
,I/BtConnectorHelper( 3870): Disconnect outgoing peer: 34:FC:EF:11:AE:67
,I/BtToSocketBase( 3870): Stop ReceivingThread,
,I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
I/BtToSocketBase( 3870): Close localHostSocket,
I/BtToSocketBase( 3870): Close bt in
,I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
I/BtToRequestSocket( 3870): Close server socket,
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3870): 2015-11-24T12:40:51.853Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3870): 
,I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.856Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:40:51.856Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:40:51.857Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 144023 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
W/bt-btif ( 2201): invalid rfc slot id: 41
I/BtToSocketBase( 3870): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3870): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT6814
,I/BtToSocketBase( 3870): Stop ReceivingThread
I/BtToSocketBase( 3870): Stop SendingThread
I/BtToSocketBase( 3870): Close local in
I/BtToSocketBase( 3870): Close LocalOutputStream
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/BtToSocketBase( 3870): Close localHostSocket
I/BtToSocketBase( 3870): Close bt in
I/BtToSocketBase( 3870): Close bt out
,I/BtToSocketBase( 3870): Close bt socket
W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
I/BtToSocketBase( 3870): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3870): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3870): 2015-11-24T12:40:51.882Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 8 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
,I/SS      ( 3870): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 49
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:41:01.804Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:41:01.804Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:41:01.806Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1134): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/jxcore-log( 3870): 2015-11-24T12:41:06.809Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:06.810Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:41:11.814Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:41:11.815Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:11.816Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:11.816Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/SS      ( 3870): Found 7 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 1134): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btm  ( 2201): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f925dc rs_disc_pending=2
E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1541): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1541): Bluetooth Device Name: Nexus 5
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,--------- beginning of crash
F/libc    ( 1134): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1134 (wpa_supplicant)
I/libc    ( 1134): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,I/        ( 3870): Cleared service requests
,D/WifiHW  (  822): 'P2P_FIND 120' command timed out.
,I/        ( 3870): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  822): Connection lost, restart supplicant
,E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): failed to set BSSID: any
E/native  (  822): do suspend true
,D/CommandListener(  355): Clearing all IP addresses on wlan0
W/Settings( 1816): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NativeCrypto( 1274): Read error: ssl=0xaec62600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1274): SSL shutdown failed: ssl=0xaec62600: I/O error during system call, Broken pipe
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/jxcore-log( 3870): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3870): 
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
I/jxcore-log( 3870): The Coordinator has disconnected!
I/jxcore-log( 3870): 
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  822): Unexpected BatchedScanResults :null
,D/WifiScanningService(  822): SCAN_AVAILABLE : 1
,D/RttService(  822): SCAN_AVAILABLE : 1
D/RttService(  822): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): DefaultState
I/        ( 3870): Discovery state changed to Stopped.
,I/SS      ( 3870): We got empty peers list
D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
I/        ( 3870): Starting peer discovery failed, error code 2
,I/WB      ( 3870): Wifi is DISABLED !!
I/        ( 3870): Stoping All
I/        ( 3870): Stopping services
I/        ( 3870): Stopping services
,I/        ( 3870): Stop Bluetooth
I/        ( 3870): Stop Bluetooth
I/BTListenerThread( 3870): Stopped
E/bt-btif ( 2201): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:50, channel:-1
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:41:43.485Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:43.486Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:43.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
I/        ( 3870): Clearing local services failed, error code 2
I/        ( 3870): Clearing service requests failed, error code 2
I/        ( 3870): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,I/ActivityManager(  822): Start proc 4332:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  822): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
W/ResourcesManager( 4332): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/GpsLocationProvider(  822): No APN found to select.
,I/Babel_SMS( 4332): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4332): MmsConfig.loadMmsSettings
I/Babel_SMS( 4332): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,I/Babel_SMS( 4332): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4332): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4332): MmsConfig.loadFromResources
E/Babel_SMS( 4332): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4332): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,I/art     (  822): Explicit concurrent mark sweep GC freed 60325(2MB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.442ms total 59.182ms
,W/Settings( 4332): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 4332): startup - clean
,I/Babel   ( 4332): deleted: false for 0
,I/Babel_telephony( 4332): TeleModule.launchCompleted
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 4332): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 4332): BAM#gBA: invalid account id: -1
W/Babel   ( 4332): BAM#gBA: invalid account id: -1
I/Babel_telephony( 4332): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,W/VideoCapabilities( 4332): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  822): Start proc 4362:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,I/VideoCapabilities( 4332): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4332): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4332): Unrecognized profile 2130706433 for video/avc
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 50
,W/VideoCapabilities( 4332): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4332): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  822): Killing 3398:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/MusicStore( 4362): Database version: 120
,I/vclib   ( 4332): onServiceConnected
W/Babel   ( 4332): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4362): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4362): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4362): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4362): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 4362): GMSCore installation verified
,I/ConfigStore( 4362): Config Database version: 1
,I/MediaRouter( 4362): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 4362): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Start proc 4392:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 4362): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4362): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 4392): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3870): 
,D/WifiService(  822): setWifiEnabled: false pid=3870, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,D/SprintDMHelper( 4392): simOperator:  IMSI: null
,D/SprintDMReceiver( 4392): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1848): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1848): onCreate
,I/ActivityManager(  822): Killing 3220:android.process.acore/u0a5 (adj 15): empty #17
,D/WifiService(  822): setWifiEnabled: true pid=3870, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  822): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 477ms
,I/jxcore-log( 3870): Wifi toggled for connection repairment
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SystemUpdateService( 1848): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1848): active receiver: enabled
,I/SystemUpdateService( 1848): showing system update notification
,I/iu.Environment( 1848): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1848): num queued entries: 0
I/iu.UploadsManager( 1848): num updated entries: 0
I/iu.SyncManager( 1848): NEXT; no task
I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1848): retry (wakeup: false) in 3599964 ms
,D/ChimeraCfgMgr( 1848): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1848): onDestroy
,I/ActivityManager(  822): Start proc 4417:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 4332): connection state changed from UNKNOWN to DISCONNECTED
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 17.169ms
,I/ActivityManager(  822): Killing 3680:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 354us total 15.157ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 223us total 12.718ms
,D/WifiController(  822): DEFERRED_TOGGLE handled,
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
D/CommandListener(  355): Trying to bring down wlan0
,D/Tethering(  822): InitialState.processMessage what=4
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/Tethering(  822): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  822): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  822): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/wpa_supplicant( 4434): Successfully initialized wpa_supplicant
,I/GAv4    ( 4417): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4417):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4417):   adb logcat -s GAv4
,W/GAv4    ( 4417): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/wpa_supplicant( 4434): rfkill: Cannot open RFKILL control device
,W/GAv4    ( 4417): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4417): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4417): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4417): Time to load native libraries: 1 ms (timestamps 5946-5947)
I/LibraryLoader( 4417): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4417): Binding Chromium to main looper Looper (main, tid 1) {2920bc0b}
I/LibraryLoader( 4417): Expected native library version number "",actual native library version number ""
I/chromium( 4417): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4417): Initializing chromium process, singleProcess=true
,W/art     ( 4417): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4417): ApplicationContext is null in ApplicationStatus
,D/Tethering(  822): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4434): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4434): Could not read interface p2p-dev-wlan0 flags: No such device
,W/chromium( 4417): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4417): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 4417): Starting up...
W/AudioManagerAndroid( 4417): Requires BLUETOOTH permission
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/ActivityManager(  822): Killing 3702:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 4475:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,D/WifiConfigStore(  822): Loading config and enabling all networks ,
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@251cfa9a}
,E/WifiConfigStore(  822): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  822): Setting external_sim to 1
W/Settings( 4332): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  822): Setting OUI to 92-68-C3
,I/WifiNative-HAL(  822): startHal
D/wifi    (  822): setting scan oui 0xaec73670
D/WifiHAL (  822): Sending mac address OUI
,E/native  (  822): do suspend true
,W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  822): SCAN_AVAILABLE : 3
D/RttService(  822): SCAN_AVAILABLE : 3
D/WifiScanningService(  822): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL(  822): startHal
D/wifi    (  822): getting scan capabilities on interface[0] = 0xaec73670
D/WifiHAL (  822): Creating message to get scan capablities; iface = 5
D/WifiHAL (  822): In GetCapabilities::handleResponse
,D/RttService(  822): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHAL (  822): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  822): StartedState
D/CommandListener(  355): Setting iface cfg
,E/WifiP2pService(  822): Unable to change interface settings: java.lang.IllegalStateException: command '58 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 58 Failed to set address (No such device)'
D/WifiMonitor(  822): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3870): Wifi is now enabled !
,I/        ( 3870): Stoping All
,I/        ( 3870): Stopping services
I/        ( 3870): Stop Bluetooth
I/        ( 3870): Starting All
I/        ( 3870): Stopping services
I/        ( 3870): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@35a07d5e
I/        ( 3870): Stopping services
I/        ( 3870): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}
I/        ( 3870): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, length : 80
I/        ( 3870): peerDiscoveryTimer timeout value:7281
,I/        ( 3870): Stop Bluetooth
I/        ( 3870): StartBluetooth listener
I/        ( 3870): StartBluetooth listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Discovery state changed to Stopped.
,I/BTListenerThread( 3870): starting to listen
I/BTListenerThread( 3870): waiting to accept incoming Connection
,I/wpa_supplicant( 4434): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  822): p2pGetDeviceAddress
D/WifiNative-HAL(  822): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/        ( 3870): Added local service
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Stopped peer discovery
I/        ( 3870): Started peer discovery
,I/        ( 3870): Discovery state changed to Started.
,I/        ( 3870): Started peer discovery
,V/MusicLeanback( 4362): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  822): Killing 3419:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/SprintDMReceiver( 4392): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4392): simOperator:  IMSI: null
D/SprintDMReceiver( 4392): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1848): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1848): onCreate
,D/SystemUpdateService( 1848): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1848): active receiver: enabled
,I/SystemUpdateService( 1848): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,D/ChimeraCfgMgr( 1848): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1848): retry (wakeup: false) in 3599942 ms
,D/SystemUpdateService( 1848): onDestroy
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  822):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  822):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,I/jxcore-log( 3870): 2015-11-24T12:41:48.487Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:48.487Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  822): Start proc 4507:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 4362): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 4362): Stop autocaching.
,W/ResourcesManager( 4507): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4507): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4507): VM with version 2.1.0 has multidex support
,I/MultiDex( 4507): install
I/MultiDex( 4507): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4507): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4507): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1274): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1274): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WearableService( 4507): callingUid 10011, callindPid: 4507
,V/GmsCoreStatsServiceLauncher( 1848): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1848): Restart initialization of location
,E/MDM     ( 1816): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4362): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 4362): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/wpa_supplicant( 4434): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4434): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4434): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=],
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
E/WifiStateMachine(  822): Start Dhcp Watchdog 2
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 0
E/WifiStateMachine(  822):  RSSI mgmt: -44
E/WifiStateMachine(  822):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 0 tx_time=172 rx_time=268 scan_time=0
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/wpa_supplicant( 4434): P2P-FIND-STOPPED 
,I/        ( 3870): Discovery state changed to Stopped.
I/        ( 3870): Starting peer discovery failed, error code 2
,I/dhcpcd  ( 4541): version 5.5.6 starting
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@251cfa9a}
,I/dhcpcd  ( 4541): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 4541): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4541): wlan0: leased 192.168.1.110 for 86400 seconds
,E/native  (  822): do suspend true
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 101
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  822): Setting Dns servers for network 101 to [/192.168.1.1],
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  822):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 4362): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1357): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,V/MusicLeanback( 4362): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  822): No APN found to select.
,D/SprintDMReceiver( 4392): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4392): simOperator:  IMSI: null
D/SprintDMReceiver( 4392): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1848): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1848): onCreate
,D/SystemUpdateService( 1848): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1848): active receiver: enabled
,I/SystemUpdateService( 1848): showing system update notification
,I/iu.Environment( 1848): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/jxcore-log( 3870): 2015-11-24T12:41:53.489Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:53.489Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:41:53.490Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:53.490Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/ChimeraCfgMgr( 1848): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ValidateNoPeople(  822): skipping global notification
,I/iu.UploadsManager( 1848): num queued entries: 0
,I/iu.UploadsManager( 1848): num updated entries: 0
,V/SystemUpdateService( 1848): retry (wakeup: false) in 3599967 ms
,I/iu.SyncManager( 1848): NEXT; no task
,D/ChimeraCfgMgr( 1848): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1848): onDestroy
,I/art     (  822): Explicit concurrent mark sweep GC freed 50116(2MB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.493ms total 100.081ms
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1848): [AccountUtils] Account not ready
W/Kids    ( 1848): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1848): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1848): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1848): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1848): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1848): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1848): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1848): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1848): 	at java.lang.Thread.run(Thread.java:818)
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 24 Nov 2015 12:41:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448368913604], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448368913584]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  822): Validated
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,V/Herrevad( 1848): NQAS connected
,I/art     ( 1816): Explicit concurrent mark sweep GC freed 21038(1204KB) AllocSpace objects, 10(160KB) LOS objects, 37% free, 26MB/42MB, paused 883us total 31.640ms
,E/DataBuffer( 1816): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1dc11844)
,I/Babel   ( 4332): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1274): Connected
,D/GCM     ( 1274): Message class com.google.f.a.a.p
,I/jxcore-log( 3870): DBG, CoordinatorConnector connect called
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Coordinator is now connected to the server!
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,D/ConnectivityService(  822): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 1 peers.,
I/SS      ( 3870): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/ActivityManager(  822): Killing 3732:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x10  CID 0x46
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 52
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:41:59.372Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:41:59.373Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:41:59.373Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 49263(2MB) AllocSpace objects, 9(993KB) LOS objects, 37% free, 27MB/43MB, paused 1.975ms total 58.269ms,
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1040012, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/jxcore-log( 3870): 2015-11-24T12:42:04.375Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:04.376Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/        ( 3870): Discovery state changed to Started.
,I/jxcore-log( 3870): 2015-11-24T12:42:09.378Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:09.379Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:09.380Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:09.380Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 3 peers.
I/SS      ( 3870): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(3): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery,
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 4 peers.
I/SS      ( 3870): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(2): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(4): G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,V/GoogleAuthProtoRequest( 3083): [317] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3083): [317] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3083): [317] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3083): [318] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3083): [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3083): [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3083): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3083): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3083): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3083): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3083): 	at com.a.a.k.run(SourceFile:110)
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 53
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:42:40.043Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
,I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:40.045Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): 2015-11-24T12:42:40.047Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/jxcore-log( 3870): 2015-11-24T12:42:45.048Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:45.049Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
,I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3870): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:42:50.052Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:50.053Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:50.053Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:50.054Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 54
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/jxcore-log( 3870): 2015-11-24T12:42:55.209Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:55.210Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:55.215Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:55.219Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- gotta redo : F8:95:C7:87:85:54, try count now: 2
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:42:55.223Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:55.224Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:55.224Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 123355 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63),
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 55
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3870): 2015-11-24T12:42:56.256Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed,
I/jxcore-log( 3870): ,
,I/jxcore-log( 3870): 2015-11-24T12:42:56.257Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:42:56.258Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1071617, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3870): 2015-11-24T12:43:01.259Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:01.259Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(3): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(5): G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:43:06.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:06.263Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:06.264Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): 2015-11-24T12:43:06.264Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3870): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 56
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:43:09.569Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:09.571Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:09.571Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:43:14.572Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:14.573Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 3870): 2015-11-24T12:43:19.577Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:19.578Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:19.579Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:19.579Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 57
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:43:20.528Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:20.528Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:20.529Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3870): Found 5 peers.
I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:43:25.530Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:25.531Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1848): Handling authorization failure
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
,V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1119957, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3870): 2015-11-24T12:43:30.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:30.535Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:30.536Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:30.536Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 58
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:43:30.792Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:30.792Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:30.793Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:43:35.793Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:35.794Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 7 peers.,
I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(3): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3870): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(5): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3870): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(7): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/jxcore-log( 3870): 2015-11-24T12:43:40.798Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:40.799Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:43:40.799Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:43:40.800Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/art     (  822): Explicit concurrent mark sweep GC freed 38276(1654KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 2.683ms total 91.840ms
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3870): Found 7 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_608e 92:e7:c4:e6:4c:f8
,I/SS      ( 3870): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(5): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 59
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:44:11.552Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:11.553Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:11.557Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:11.561Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 2
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:11.562Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): 2015-11-24T12:44:11.562Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:11.562Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 76330 ms, rnd: 5, ex: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10,
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 60
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:44:12.212Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:12.213Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:12.213Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:44:17.214Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:17.215Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/SS      ( 3870): Found 7 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3870): 2015-11-24T12:44:22.219Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:22.220Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:22.220Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:22.221Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 61
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:44:24.000Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:24.001Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:24.001Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:44:29.002Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:29.003Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1848): Handling authorization failure
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
,V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1162921, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): ,	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	,at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1162867, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3870): 2015-11-24T12:44:34.006Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:34.007Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:34.007Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:34.008Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 62
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:44:35.594Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:35.595Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:35.595Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 7 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:44:40.596Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:40.597Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:45.601Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:45.602Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:45.602Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:45.603Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 63
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:44:46.492Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:46.493Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:46.494Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/SS      ( 3870): Found 4 peers.
,I/SS      ( 3870): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3870): Peer(4): S5-1 ee:1f:72:63:11:86
D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:44:51.497Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:51.498Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:56.502Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:56.502Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:56.503Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:56.503Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 64
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:44:56.724Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:56.725Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:56.729Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:56.731Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 2
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): ,
I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:56.734Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:56.735Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:56.735Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 45163 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 65
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:44:57.837Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:44:57.838Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:44:57.839Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
,E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82),
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	,at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38)
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1197857, reason: 10074, SyncResult: stats [ numIoExceptions: 1],
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3870): 2015-11-24T12:45:02.840Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:02.841Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/jxcore-log( 3870): 2015-11-24T12:45:07.844Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:07.845Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:07.845Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:07.846Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 66
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:45:09.208Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:09.209Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:09.209Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 4 peers.
,I/SS      ( 3870): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3870): Peer(4): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:45:14.210Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:14.211Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E,
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/jxcore-log( 3870): 2015-11-24T12:45:19.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:19.216Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:19.217Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:19.217Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 67
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:45:19.425Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:19.426Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:19.426Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:45:24.428Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:24.429Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3870): 2015-11-24T12:45:29.432Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:29.433Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:29.433Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:29.434Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null,
,I/BTConnectToThread( 3870): Starting to connect
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 6 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3870): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 7 peers.
I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x22  CID 0x46
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 68
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:45:59.776Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:45:59.777Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:45:59.778Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 61066(3MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 798us total 29.299ms
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1848): Handling authorization failure
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
,V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38)
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1252947, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1255154, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery,
,I/jxcore-log( 3870): 2015-11-24T12:46:04.779Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:04.780Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:09.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:09.783Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:09.784Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:09.784Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x10  CID 0x4b
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 69
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:46:15.299Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:15.299Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:15.304Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:15.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- gotta redo : F8:95:C7:87:85:54, try count now: 3
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:15.312Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:15.313Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
,I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:15.313Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): ,
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 78565 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp,
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 70
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:46:16.556Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:16.557Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:16.557Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3870): 2015-11-24T12:46:21.558Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:21.559Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3870): Found 7 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d,
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b,
D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3870): 2015-11-24T12:46:26.562Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:26.562Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:26.563Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:26.563Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  822): Explicit concurrent mark sweep GC freed 46084(2MB) AllocSpace objects, 14(601KB) LOS objects, 31% free, 34MB/50MB, paused 1.443ms total 87.100ms
,W/bt-btif ( 2201): info:x10,
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp,
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2201): invalid rfc slot id: 71
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:46:28.232Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:28.233Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:28.233Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/jxcore-log( 3870): 2015-11-24T12:46:33.234Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:33.235Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:38.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:38.240Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:38.241Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:38.241Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null,
,I/BTConnectToThread( 3870): Starting to connect,
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10,
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp,
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 2201): invalid rfc slot id: 72
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:46:39.368Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:39.368Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:39.369Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 7 peers.
I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/jxcore-log( 3870): 2015-11-24T12:46:44.370Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:44.371Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery,
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E,
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3870): 2015-11-24T12:46:49.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:49.375Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:49.375Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:49.376Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 73
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:46:50.631Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:46:50.632Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:50.632Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL,
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032,
,I/jxcore-log( 3870): 2015-11-24T12:46:55.633Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:46:55.634Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): ,
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1315727, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3870): 2015-11-24T12:47:00.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:00.639Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:00.640Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:00.640Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3870): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/SS      ( 3870): Found 7 peers.,
I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3870): Peer(5): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/WifiP2pManager( 3870): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 74
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:47:01.041Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:01.042Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:01.047Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:01.051Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 3
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:01.058Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:01.058Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:01.059Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 45729 ms, rnd: 5, ex: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 6, f, 410d
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92414 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 75
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:47:02.875Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:02.876Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:02.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92414 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3870): 2015-11-24T12:47:07.879Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:07.879Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3870): 2015-11-24T12:47:12.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:12.885Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:12.886Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:12.886Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null,
,I/BTConnectToThread( 3870): Starting to connect,
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 76
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:47:14.214Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:14.215Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:14.215Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3870): 
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 3870): 2015-11-24T12:47:19.216Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:19.217Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/jxcore-log( 3870): 2015-11-24T12:47:24.222Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:24.222Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:24.223Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:24.223Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null,
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 77
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:47:25.209Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:25.210Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:25.211Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 6 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/jxcore-log( 3870): 2015-11-24T12:47:30.213Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41,
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:30.213Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
,E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38),
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1345267, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3870): 2015-11-24T12:47:35.217Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:35.218Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:35.219Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:35.219Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41,
I/BTConnectToThread( 3870): Starting to connect
W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 2201): info:x10
D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp,
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 78
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:47:35.706Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:35.706Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:35.707Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3870): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): 2015-11-24T12:47:40.708Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:40.709Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:45.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:45.714Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:45.714Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:45.715Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: 08:EC:A9:50:75:41, name: null,
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3870): Connecting to null, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,W/bt-btif ( 2201): info:x10,
D/        ( 2201): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 79
I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3870): 2015-11-24T12:47:47.509Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:47.509Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:47.517Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:47.520Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3870): 
I/jxcore-log( 3870): ---- round done--------
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 3
I/jxcore-log( 3870): 
I/jxcore-log( 3870): do fake peer & start
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:47.525Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:47.527Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:47.528Z SendDataConnector.js: do connect now
I/jxcore-log( 3870): 
,I/        ( 3870): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3870): Starting to connect
,W/BluetoothAdapter( 3870): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3870): Connecting to null, at F8:95:C7:87:85:54
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback round[0] time: 46452 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa2f92414 rs_disc_pending=1
,W/bt-btif ( 2201): bta_dm_check_av:0
W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 80
,I/BTConnectToThread( 3870): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3870): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3870): 2015-11-24T12:47:47.965Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:47.966Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:47.967Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3870): 
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28,
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3870): timeout now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): dun
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): weAreDoneNow , resultArray.length: 11
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): done, now sending data to server
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): -- RESULT DATA {"name:":"motorola-Nexus 6_PT89","time":1000099,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":10609,"result":"OK","connections":1,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":49848,"result":"OK","connections":2,"tryCount":1},{"name":"58:2A:F7:ED:96:BE","time":21848,"result":"OK","connections":2,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":7289,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:37:96:AB","time":50606,"result":"OK","connections":2,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":6953,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":2525,"result":"OK","connections":1,"tryCount":1},{"name":"08:EC:A9:50:76:27","time":8203,"result":"OK","connections":1,"tryCount":1},{"name":"90:E7:C4:F6:69:77","time":17643,"result":"OK","connections":2,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":5286,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:11:AE:67","time":144023,"result":"OK","connections":4,"tryCount":1
,I/jxcore-log( 3870): sendList : 100% : 144023 ms, 99% : 144023 ms, 95 : 50606 ms, 90% : 50606 ms.
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Result count 11, range 2525 ms to  144023 ms.
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): sendList failed peers count : 3 [21.428571428571427 %]
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): - Peer ID : F8:95:C7:87:85:54, Tried : 4
I/jxcore-log( 3870): 
I/jxcore-log( 3870): - Peer ID : F8:95:C7:87:3C:51, Tried : 3
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): - Peer ID : 08:EC:A9:50:75:41, Tried : 3
I/jxcore-log( 3870): 
I/jxcore-log( 3870): sendList never tried peers count : 0 [0 %],
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:52.168Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:47:52.168Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3870): 
I/jxcore-log( 3870): 2015-11-24T12:47:52.169Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3870): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,V/KeepSync( 3775): Connecting to GoogleApiClient
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1848): Handling authorization failure,
E/ClientConnectionOperation( 1848): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62),
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1848): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1848): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1848): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97),
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1848): ,	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1848): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1848),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1848): 	... 7 more
V/KeepSync( 3775): GoogleApiClient failed to connect with error code: 4,
E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3775): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3775): IOException
E/KeepSync( 3775): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3775): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3775): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3775): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3775): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3775): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3775): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3775): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3775): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3775): 	... 10 more
W/KeepSync( 3775): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1409860, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Cleared service requests
I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3870): Found 6 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 6 peers.
I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at blb.a(PG:3937)
E/HttpOperation( 3200): 	at czp.a(PG:18188)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 12 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 14 more
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3200): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3200): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3200): 	at jdm.a(PG:82)
E/HttpOperation( 3200): 	at jcs.o(PG:406)
E/HttpOperation( 3200): 	at jcn.a(PG:1379)
E/HttpOperation( 3200): 	at jcs.i(PG:143)
E/HttpOperation( 3200): 	at hec.a(PG:42)
E/HttpOperation( 3200): 	at hee.a(PG:102)
E/HttpOperation( 3200): 	at czr.a(PG:65)
E/HttpOperation( 3200): 	at kka.a(PG:108)
E/HttpOperation( 3200): 	at czp.a(PG:19176)
E/HttpOperation( 3200): 	at czp.a(PG:9081)
E/HttpOperation( 3200): 	at czq.run(PG:1686)
E/HttpOperation( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3200): 	at jdj.a(PG:4091)
E/HttpOperation( 3200): 	at jdj.a(PG:1125)
E/HttpOperation( 3200): 	at jdm.a(PG:77)
E/HttpOperation( 3200): 	... 15 more
E/HttpOperation( 3200): Caused by: faj: BadAuthentication
E/HttpOperation( 3200): 	at fal.a(PG:38)
E/HttpOperation( 3200): 	at jdj.a(PG:4089)
E/HttpOperation( 3200): 	... 17 more
,E/ExperimentLoader( 3200): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3200): 	at jdm.a(PG:82)
E/ExperimentLoader( 3200): 	at jcs.o(PG:406)
E/ExperimentLoader( 3200): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3200): 	at jcs.i(PG:143)
E/ExperimentLoader( 3200): 	at hec.a(PG:42)
E/ExperimentLoader( 3200): 	at hee.a(PG:102)
E/ExperimentLoader( 3200): 	at czr.a(PG:65)
,E/ExperimentLoader( 3200): 	at kka.a(PG:108)
E/ExperimentLoader( 3200): 	at czp.a(PG:19176)
E/ExperimentLoader( 3200): 	at czp.a(PG:9081)
E/ExperimentLoader( 3200): 	at czq.run(PG:1686)
E/ExperimentLoader( 3200): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3200): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3200): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3200): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3200): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3200): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3200): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3200): 	at jdm.a(PG:77)
E/ExperimentLoader( 3200): 	... 15 more
E/ExperimentLoader( 3200): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3200): 	at fal.a(PG:38)
E/ExperimentLoader( 3200): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3200): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1499799, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3870): Found 6 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3870): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b,
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3870): Cleared service requests,
I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 3 peers.,
I/SS      ( 3870): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3870): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request,
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3870): Started service discovery,
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3870): Cleared service requests
I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 3 peers.
,I/SS      ( 3870): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3870): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 4 peers.
,I/SS      ( 3870): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,W/bt-btm  ( 2201): Stopping oneshot timer
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3870): Found 4 peers.
,I/SS      ( 3870): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3870): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/BooksSync( 3792): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3792): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 56125(2MB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 2.452ms total 78.587ms
,I/GLSUser ( 1274): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1274): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1274): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1274): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1274): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3792): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3792): Soft error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3792): Sync error
E/BooksSync( 3792): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3792): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3792): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1591137, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Cleared service requests
,I/        ( 3870): Started peer discovery
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3870): Found 5 peers.
,I/SS      ( 3870): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3870): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3870): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3870): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3870): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3870): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3870): Added service request
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/HeadsetStateMachine( 2201): Disconnected process message: 10, size: 0
,I/        ( 3870): Started service discovery
,I/wpa_supplicant( 4434): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3870): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6814, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6814, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3870): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3870): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3870): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3870): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3870): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3870): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3870): DBG, CoordinatorConnector command called
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): stop tests now !
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): stop current!
I/jxcore-log( 3870): 
I/jxcore-log( 3870): testSendData stopped
I/jxcore-log( 3870): 
,I/        ( 3870): Stoping All
,I/        ( 3870): Stopping services
I/        ( 3870): Stopping services
I/        ( 3870): Stop Bluetooth
I/        ( 3870): Stop Bluetooth
,I/BTListenerThread( 3870): Stopped
I/jxcore-log( 3870): StopBroadcasting went ok
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): 2015-11-24T12:52:12.118Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3870): 
,I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3870): DBG, CoordinatorConnector command called
I/jxcore-log( 3870): 
I/jxcore-log( 3870): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":2525,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":5286,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":6953,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":7289,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"08:EC:A9:50:76:27\",\"time\":8203,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":10609,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"90:E7:C4:F6:69:77\",\"time\":17643,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":21848,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"80:01:84:8A:B3:68\",\"time\":49848,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"7C:F9:0E:37:96:AB\",\"time\":
,I/jxcore-log( 3870): ****TEST TOOK:  ms ****
I/jxcore-log( 3870): 
,I/jxcore-log( 3870): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3870): 
I/jxcore-log( 3870): stop tests now !
I/jxcore-log( 3870): 
I/jxcore-log( 3870): end, event received
,I/jxcore-log( 3870): 
I/jxcore-log( 3870): CoordinatorConnector close called
I/jxcore-log( 3870): 
I/jxcore-log( 3870): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3870): 
I/jxcore-log( 3870): The Coordinator has disconnected!
I/jxcore-log( 3870): 
I/jxcore-log( 3870): The Coordinator has closed!
I/jxcore-log( 3870): 
I/jxcore-log( 3870): stop tests now !
I/jxcore-log( 3870): 
I/jxcore-log( 3870): turning Radios off
I/jxcore-log( 3870): 
I/jxcore-log( 3870): Toggling radios to false
I/jxcore-log( 3870): 
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@b4ac818 mBinding = false
D/BluetoothManagerService(  822): Message: 2
D/BluetoothManagerService(  822): Sending off request.
D/BluetoothAdapterState( 2201): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2201): Setting state to 13
I/BluetoothAdapterState( 2201): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2201): onBluetoothDisable()
I/BluetoothAdapterState( 2201): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 2201): Scan Mode:20
D/BluetoothAdapterState( 2201): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 12 -> 13
V/BluetoothMapMasInstance( 2201): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2201): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2201): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2201): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2201): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2201): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2201): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2201): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
W/bt-btif ( 2201): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2201): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2201): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 2201): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothMapService( 2201): onReceive
D/BluetoothMapService( 2201): STATE_TURNING_OFF
D/BluetoothMapService( 2201): MAP Service closeService in
D/BluetoothMapMasInstance( 2201): MAP Service shutdown
I/BtOppRfcommListener( 2201): stopping Accept Thread
I/BtOppRfcommListener( 2201): BluetoothSocket listen thread finished
I/chromium( 3870): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
W/ContextImpl( 4046): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/ActivityManager(  822): Start proc 4777:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  822): Message: 30
D/BluetoothManagerService(  822): Message: 30
D/LocalBluetoothProfileManager( 4046): Adding local MAP profile
D/BluetoothMap( 4046): Create BluetoothMap proxy object
D/BluetoothManagerService(  822): Message: 30
D/BluetoothManagerService(  822): Message: 30
D/LocalBluetoothProfileManager( 4046): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 4046): finishStartingService: stopping service
D/BluetoothInputDevice( 4046): Proxy object connected
D/HidProfile( 4046): Bluetooth service connected
D/BluetoothPan( 4046): BluetoothPAN Proxy object connected
D/PanProfile( 4046): Bluetooth service connected
D/BluetoothMap( 4046): Proxy object connected
D/MapProfile( 4046): Bluetooth service connected
D/BluetoothMap( 4046): getConnectedDevices()
D/BluetoothMap( 4046): Bluetooth is Not enabled
,W/bt-btif ( 2201): ag scb idx 1 not allocated
E/bt-btif ( 2201): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2201): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2201): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2201): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2201): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2201): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2201): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2201): RX termination
W/bt_userial( 2201): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2201): Leaving userial_read_thread()
,D/bt_userial( 2201): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2201): hw_epilog_process
I/bt_userial_vendor( 2201): device fd = 53 close
,D/AndroidRuntime( 4797): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4797): CheckJNI is OFF
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 59598(3MB) AllocSpace objects, 12(1323KB) LOS objects, 36% free, 27MB/43MB, paused 1.427ms total 55.155ms
,I/GKI_LINUX( 2201): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2201): GKI_exit_task 0 done
I/GKI_LINUX( 2201): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2201): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2201): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 2201): Exit Disconnected: -1
D/BluetoothHeadset( 1357): Proxy object disconnected
D/BluetoothHeadset( 1064): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/A2dpService( 2201): Received stop request...Stopping profile...
D/A2dpStateMachine( 2201): Exit Disconnected: -1
,D/BluetoothA2dp(  822): Proxy object disconnected
,D/BluetoothAdapterState( 2201): Stopping profile services that were post enabled
,D/BluetoothA2dp( 1064): Proxy object disconnected
D/HidService( 2201): Received stop request...Stopping profile...
D/BluetoothInputDevice( 1064): Proxy object disconnected
D/BluetoothInputDevice( 4046): Proxy object disconnected
D/HidProfile( 4046): Bluetooth service disconnected
D/HeadsetStateMachine( 2201): Unbinding service...
W/BluetoothHeadsetServiceJni( 2201): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2201): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2201): Received stop request...Stopping profile...
D/PanService( 2201): Received stop request...Stopping profile...
D/BluetoothPan( 1064): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 2201): handleDebugAction() action=null
D/BtGatt.GattService( 2201): Received stop request...Stopping profile...
D/BtGatt.GattService( 2201): stop()
D/BluetoothPan( 4046): BluetoothPAN Proxy object disconnected
D/PanProfile( 4046): Bluetooth service disconnected
D/BtGatt.AdvertiseManager( 2201): advertise clients cleared
,I/GKI_LINUX( 2201): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2201): GKI_exit_task 2 done
,I/GKI_LINUX( 2201): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 2201): Received stop request...Stopping profile...
D/BluetoothMapService( 2201): stop()
D/BluetoothMapEmailAppObserver( 2201): deinitObservers()
D/BluetoothMapEmailAppObserver( 2201): removeReceiver()
,W/BluetoothHidServiceJni( 2201): Cleaning up Bluetooth HID Interface...,
W/bt-btif ( 2201): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2201): Cleaning up Bluetooth GID callback object
D/BluetoothMap( 1064): Proxy object disconnected
W/BluetoothHealthServiceJni( 2201): Cleaning up Bluetooth Health Interface...,
W/BluetoothHealthServiceJni( 2201): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2201): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2201): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 2201): MAP Service closeService in
,D/BluetoothMap( 4046): Proxy object disconnected
D/MapProfile( 4046): Bluetooth service disconnected
D/BluetoothAdapterState( 2201): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2201): Setting state to 10
I/BluetoothAdapterState( 2201): Bluetooth adapter state changed: 13-> 10
,D/BluetoothMapService( 2201): cleanup()
D/BluetoothMapService( 2201): MAP Service closeService in
D/BluetoothManagerService(  822): Message: 60,
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(false) to 17 receivers.
I/BluetoothAdapterState( 2201): Entering OffState
D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1064): 
E/BluetoothA2dpSink( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@2ae5d0d,
E/BluetoothA2dpSink( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
,E/BluetoothA2dpSink( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1064): 
E/BluetoothHeadsetClient( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@9a5c4c2
E/BluetoothHeadsetClient( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
,E/BluetoothHeadsetClient( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dp(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1064): onBluetoothStateChange: up=false
D/BluetoothPbap( 4046): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=false
,E/BluetoothAvrcpController( 1064): 
E/BluetoothAvrcpController( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@d9412d3
E/BluetoothAvrcpController( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1064): ,	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 1357): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1064): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4046): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false,
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothMap( 4046): onBluetoothStateChange: up=false
D/BluetoothMap( 1064): onBluetoothStateChange: up=false
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothManagerService(  822): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  822): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@b4ac818 mBinding = false,
D/BluetoothManagerService(  822): Sending unbind request.
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapter( 1064): 338120909: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 338120909: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 2201): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2201): GKI_exit_task 1 done
,I/GKI_LINUX( 2201): GKI_shutdown(): task [BTIF] terminated
,D/AndroidRuntime( 4797): Calling main entry com.android.commands.pm.Pm
,D/BluetoothAdapter( 1064): 338120909: getState() :  mService = null. Returning STATE_OFF
,I/BluetoothServiceJni( 2201): cleanupNative: return from cleanup
,I/art     ( 2201): System.exit called, status: 0
I/AndroidRuntime( 2201): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3870:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  822): Skipping PackageSetting{3864c290 com.example.hello/10272} due to missing metadata
,W/ActivityThread( 4777): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/StrictMode( 4777): StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4777): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4777): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4777): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4777): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4777): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4777): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4777): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=309 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4777): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4777): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4777): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4777): StrictMode policy violation; ~duration=307 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4777): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4777): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4777): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4777): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4777): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4777): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4777): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=303 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4777): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4777): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=261 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4777): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4777): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4777): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4777): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4777): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4777): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4777): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4777): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4777): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4777): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4777): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4777): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4777): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4777): # via Binder call with stack:
D/StrictMode( 4777): android.os.StrictMode$LogStackTrace
D/StrictMode( 4777): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4777): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4777): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4777): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4777): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4777): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4777): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4777): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4777): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4777): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4777): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4777): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4777): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4777): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4777): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4777): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4777): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4777): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4777): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4777): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4777): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4777): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4777): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4777): StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4777): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4777): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4777): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4777): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4777): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4777): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4777): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4777): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4777): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4777): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4777): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4777): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4777): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4777): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4777): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4777): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4777): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 4777): Application name is not set. Call Builder#setApplicationName.
,I/WindowState(  822): WIN DEATH: Window{30630315 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,D/AsyncChannel(  822): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
W/System.err(  822): android.os.DeadObjectException
,W/System.err(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  822): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  822): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  822): 	at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$P2pEnabledState.processMessage(WifiP2pServiceImpl.java:1098)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
W/System.err(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  822): 	at android.os.Looper.loop(Looper.java:135)
W/System.err(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  822): Force removing ActivityRecord{3d482f72 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,I/ActivityManager(  822): Process com.android.bluetooth (pid 2201) has died
,W/ActivityManager(  822): Spurious death for ProcessRecord{3d56d760 3870:com.test.thalitest/u0a265}, curProc for 3870: null
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ca2cde:true
D/TaskPersister(  822): removeObsoleteFile: deleting file=24_task.xml
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1251): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1251): run()
,I/Decoder ( 1251): createOrResetDecoder
,I/ActivityManager(  822): Killing 3633:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 83241(3MB) AllocSpace objects, 1(30MB) LOS objects, 17% free, 74MB/90MB, paused 4.404ms total 58.542ms
,I/art     ( 1541): Explicit concurrent mark sweep GC freed 52786(2MB) AllocSpace objects, 12(192KB) LOS objects, 22% free, 26MB/34MB, paused 464us total 80.841ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 16162(1064KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.757ms total 80.628ms
,I/art     (  822): WaitForGcToComplete blocked for 35.901ms for cause Explicit
,I/art     (  822): Explicit concurrent mark sweep GC freed 4902(253KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 1.504ms total 53.849ms
,D/AuthorizationBluetoothService( 1274): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ContextImpl( 4046): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ConfigService( 1274): onCreate
,I/ActivityManager(  822): Start proc 4827:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/DockEventReceiver( 4046): finishStartingService: stopping service
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3870 uid 10265
,I/Keyboard.Facilitator( 1251): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1251): run()
,W/ResourcesManager( 4827): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/Launcher.Workspace( 1390): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1390): 11683562 - stripEmptyScreens()
,V/Herrevad( 1848): NQAS connected
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1251): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1251): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1251): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1251): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1251): run()
I/StatsUtilsManager( 1251): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1251): shouldRecordStats() = Too Soon
D/AdapterServiceConfig( 4827): Adding HeadsetService
D/AdapterServiceConfig( 4827): Adding A2dpService
D/AdapterServiceConfig( 4827): Adding HidService
D/AdapterServiceConfig( 4827): Adding HealthService
D/AdapterServiceConfig( 4827): Adding PanService
D/AdapterServiceConfig( 4827): Adding GattService
D/AdapterServiceConfig( 4827): Adding BluetoothMapService
,D/AuthorizationBluetoothService( 1274): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
D/BuaReceiver( 3662): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/art     ( 4797): System.exit called, status: 0
I/AndroidRuntime( 4797): VM exiting with result code 0.
,I/ActivityManager(  822): Start proc 4851:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/LocationOracleImpl( 1541): Best location was null
,I/art     ( 1390): Explicit concurrent mark sweep GC freed 11509(661KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 4.104ms total 33.273ms
,D/AsyncChannel(  822): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
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
I/wpa_supplicant( 4434): P2P-FIND-STOPPED 
,I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b,
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 4434): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
D/AsyncChannel(  822): TODO: handle replyToMessage RemoteExceptionandroid.os.DeadObjectException
W/System.err(  822): android.os.DeadObjectException,
W/System.err(  822): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err(  822): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err(  822): 	at android.os.IMessenger$Stub$Proxy.send(IMessenger.java:89)
W/System.err(  822): 	at android.os.Messenger.send(Messenger.java:57)
W/System.err(  822): 	,at com.android.internal.util.AsyncChannel.replyToMessage(AsyncChannel.java:568)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.replyToMessage(WifiP2pServiceImpl.java:2815),
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine.access$3500(WifiP2pServiceImpl.java:477)
W/System.err(  822): 	at com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine$InactiveState.processMessage(WifiP2pServiceImpl.java:1244)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:967)
W/System.err(  822): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:790)
,W/System.err(  822): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  822): 	at android.os.Looper.loop(Looper.java:135)
W/System.err(  822): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/HotwordRecognitionRnr( 1541): Starting hotword detection.
,I/MicrophoneInputStream( 1541): mic_starting com.google.android.apps.gsa.speech.audio.u@1a6d54db
,I/AudioFlinger(  359): AudioFlinger's thread 0xb408c000 ready to run
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 1541): mic_started com.google.android.apps.gsa.speech.audio.u@1a6d54db
,D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
,W/LocationOracleImpl( 1541): Best location was null
,D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
,W/LocationOracleImpl( 1541): Best location was null
,W/LocationOracleImpl( 1541): Best location was null
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1e7b1210}
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,D/VoicemailCleanupService( 4851): Cleaning up data for package: com.test.thalitest
,I/WebViewFactory( 1541): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/FileUtils( 4851): Failed to chmod(/data/data/com.android.providers.contacts/databases/contacts2.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/ActivityManager(  822): Start proc 4891:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,E/SQLiteLog( 4851): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,I/LibraryLoader( 1541): Time to load native libraries: 2 ms (timestamps 3783-3785)
E/AndroidRuntime( 4851): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 4851): Process: android.process.acore, PID: 4851
E/AndroidRuntime( 4851): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4851): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4851): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4851): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4851): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4851): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4851): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
E/AndroidRuntime( 4851): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:209)
E/AndroidRuntime( 4851): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 4851): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 4851): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 4851): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 4851): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 4851): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4851): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/LibraryLoader( 1541): Expected native library version number "",actual native library version number ""
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,I/HotwordWorker( 1541): onReady
W/art     ( 1541): Attempt to remove local handle scope entry from IRT, ignoring
,I/ContactLocale( 4851): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,E/SQLiteDatabase( 4851): Failed to open database '/data/data/com.android.providers.contacts/databases/profile.db'.
E/SQLiteDatabase( 4851): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4851): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:292)
E/SQLiteDatabase( 4851): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/SQLiteDatabase( 4851): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1572)
E/SQLiteDatabase( 4851): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteDatabase( 4851): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4851): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Atlas   (  822): Validating map...
E/SQLiteOpenHelper( 4851): Couldn't open profile.db for writing (will try read-only):
E/SQLiteOpenHelper( 4851): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4851): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4851): 	at com.android.providers.contacts.aggregation.ContactAggregator.<init>(ContactAggregator.java:292)
E/SQLiteOpenHelper( 4851): 	at com.android.providers.contacts.aggregation.ProfileAggregator.<init>(ProfileAggregator.java:43)
E/SQLiteOpenHelper( 4851): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1572)
E/SQLiteOpenHelper( 4851): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4851): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4851): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4851): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659520275
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/SQLiteLog( 4851): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,I/Process ( 4851): Sending signal. PID: 4851 SIG: 9
,I/ActivityManager(  822): Start proc 4917:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
W/ContextImpl( 4917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,D/OpenGLRenderer(  822): Enabling debug mode 0
W/art     ( 1541): Attempt to remove local handle scope entry from IRT, ignoring
,E/SQLiteLog( 1274): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1274): Shutting down VM
E/AndroidRuntime( 1274): FATAL EXCEPTION: main
E/AndroidRuntime( 1274): Process: com.google.process.gapps, PID: 1274
E/AndroidRuntime( 1274): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1274): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1274): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1274): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1274): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1274): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1274): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1274): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1274): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1274): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1274): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1274): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1274): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1274): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1274): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1274): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1274): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1274): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1274): 	... 9 more
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,I/ActivityManager(  822): Process android.process.acore (pid 4851) has died
,W/ActivityManager(  822): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,E/SQLiteDatabase( 4917): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4917): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4917): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4917): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4917): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4917): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4917): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4917): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4917): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4917): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 4917): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4917): Process: com.android.keychain, PID: 4917
E/AndroidRuntime( 4917): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4917): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4917): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4917): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4917): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4917): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4917): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4917): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4917): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,I/HotwordDetector( 1541): Closing mic
I/MicrophoneInputStream( 1541): mic_close com.google.android.apps.gsa.speech.audio.u@1a6d54db
,E/Search.SharedPreferencesProto( 1541): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  822): Killing 3508:com.android.vending/u0a19 (adj 15): empty #17
,D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1541): Hotword detection finished
I/HotwordRecognitionRnr( 1541): Stopping hotword detection.
,E/native  ( 1251): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1251): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  822): Start proc 4954:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,E/SQLiteDatabase( 4954): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.,
E/SQLiteDatabase( 4954): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4954): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791),
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4954): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4954): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
,E/SQLiteDatabase( 4954): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 4954): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteDatabase( 4954): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641),
E/SQLiteDatabase( 4954): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteDatabase( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/SQLiteDatabase( 4954): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4954): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4954): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 4954): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4954): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4954): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4954): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4954): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4954): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 4954): 	,at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/SQLiteOpenHelper( 4954): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/SQLiteOpenHelper( 4954): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/SQLiteOpenHelper( 4954): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4954): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 4954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4954): (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,E/AndroidRuntime( 4954): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4954): Process: android.process.acore, PID: 4954
E/AndroidRuntime( 4954): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
,E/AndroidRuntime( 4954): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4954): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4954): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754),
E/AndroidRuntime( 4954): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4954): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
E/AndroidRuntime( 4954): 	,at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
E/AndroidRuntime( 4954): 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1068)
E/AndroidRuntime( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
E/AndroidRuntime( 4954): ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/AndroidRuntime( 4954): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 4954): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1561)
E/AndroidRuntime( 4954): 	,at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1641)
E/AndroidRuntime( 4954): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4954): 	,at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
,E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
,E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	,at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	,at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186),
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): ,	... 5 more
,I/ActivityManager(  822): Killing 4362:com.google.android.music:main/u0a66 (adj 15): empty #17
,E/QMI_FW  (  822): xport_send: Sendto failed for port 4096
E/LocSvc_api_v02(  822): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659520275
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,E/kickstart(  877): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1

```
