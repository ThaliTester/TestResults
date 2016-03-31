#### Test 646138038d447f5_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-31 09:43:44.449  3351  3351 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-31 09:43:44.456  3351  3351 I BooksApp: Created application version: 3.6.8 (30608)
03-31 09:43:44.495  3392  3392 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-31 09:43:44.497  1352  3443 D GCM     : Connected
03-31 09:43:44.510  1352  3443 D GCM     : Message class com.google.f.a.a.p
03-31 09:43:44.514  3392  3392 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9276-9277)
03-31 09:43:44.514  3392  3392 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 09:43:44.521  3392  3392 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f3faa1}
03-31 09:43:44.521  3392  3392 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-31 09:43:44.521  3392  3392 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 09:43:44.531  3392  3392 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 09:43:44.535  3392  3392 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 09:43:44.536  3392  3392 E SysUtils: ApplicationContext is null in ApplicationStatus
03-31 09:43:44.545  3418  3468 V KeepSync: Connecting to GoogleApiClient
03-31 09:43:44.546  3392  3392 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-31 09:43:44.552  3392  3392 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 09:43:44.552  3392  3392 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 09:43:44.552  3392  3392 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-31 09:43:44.598  3351  3462 I BooksSync: Starting books sync for 61035162, extras: ade
03-31 09:43:44.606  3392  3392 I NSApplication: Starting up...
03-31 09:43:44.612  3392  3485 W AudioManagerAndroid: Requires BLUETOOTH permission
03-31 09:43:44.625  1771  3477 I art     : Explicit concurrent mark sweep GC freed 25676(1763KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.257ms total 34.890ms
--------- beginning of system
03-31 09:43:44.644   822  1396 I ActivityManager: Start proc 3491:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
03-31 09:43:44.644   822  1396 I ActivityManager: Killing 2438:com.google.android.apps.maps/u0a65 (adj 15): empty #17
03-31 09:43:44.674  3470  3470 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 09:43:44.676  3470  3470 D AndroidRuntime: CheckJNI is OFF
03-31 09:43:44.797  3470  3470 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 09:43:44.809   822  1196 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 09:43:44.815   822  1196 V WindowManager: addAppToken: AppWindowToken{32c85fb8 token=Token{315b521b ActivityRecord{3960d42a u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-31 09:43:44.818  3470  3470 D AndroidRuntime: Shutting down VM
03-31 09:43:44.820  1771  3477 W BaseAppContext: Using Auth Proxy for data requests.
03-31 09:43:44.824  1509  1509 I HotwordDetector: Closing mic
03-31 09:43:44.825  1509  1763 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2bfea04b
03-31 09:43:44.864   822  1233 I ActivityManager: Start proc 3520:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-31 09:43:44.876  1771  3477 W BaseAppContext: Using Auth Proxy for data requests.
03-31 09:43:44.882   822   822 V ActivityManager: Display changed displayId=0
03-31 09:43:44.885   358  1769 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 09:43:44.888   358  1769 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 09:43:44.895   358  1019 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-31 09:43:44.900  1509  1764 I HotwordRecognitionRnr: Stopping hotword detection.
03-31 09:43:44.901  1509  1766 I HotwordRecognitionRnr: Hotword detection finished
03-31 09:43:44.939  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 09:43:44.939  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:44.939  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:44.939  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 09:43:44.944  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 09:43:44.952   822  1397 I ActivityManager: Killing 3005:com.google.android.partnersetup/u0a16 (adj 15): empty #17
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: Handling authorization failure
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 09:43:44.964  1771  3477 E ClientConnectionOperation: 	... 7 more
03-31 09:43:44.971  3520  3520 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-31 09:43:45.009  3351  3543 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 09:43:45.164  3418  3468 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 09:43:45.175  3418  3468 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:43:45.183  3520  3520 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9945-9946)
03-31 09:43:45.183  3520  3520 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 09:43:45.192  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 09:43:45.192  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:45.192  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:45.192  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:45.196  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:45.199  3418  3468 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 09:43:45.199  3418  3468 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 09:43:45.199  3520  3520 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fd20892}
,03-31 09:43:45.199  3520  3520 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 09:43:45.200  3520  3520 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 09:43:45.211  3520  3520 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-31 09:43:45.212  3520  3520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 09:43:45.213  3520  3520 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 09:43:45.226  3520  3520 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-31 09:43:45.234  3520  3520 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 09:43:45.234  3520  3520 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-31 09:43:45.234  3520  3520 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-31 09:43:45.245  1352  1641 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 09:43:45.245  1352  1641 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:45.245  1352  1641 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:45.245  1352  1641 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:45.258   822  2114 I ActivityManager: Start proc 3556:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-31 09:43:45.261   822  2114 I ActivityManager: Killing 3025:com.android.musicfx/u0a18 (adj 15): empty #17
,03-31 09:43:45.267   822   837 I art     : Explicit concurrent mark sweep GC freed 25854(1162KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 2.037ms total 50.786ms
,03-31 09:43:45.281   822   860 D BluetoothManagerService: Message: 20
03-31 09:43:45.281   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff6b72c:true
,03-31 09:43:45.343   822  1252 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658692883
03-31 09:43:45.343   822  1252 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-31 09:43:45.370  1352  1641 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:45.391  3351  3543 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 09:43:45.393  3351  3462 E BooksSync: Soft error
03-31 09:43:45.393  3351  3462 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:43:45.393  3351  3462 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:43:45.393  3351  3462 E BooksSync: Sync error
03-31 09:43:45.393  3351  3462 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:43:45.393  3351  3462 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:43:45.393  3351  3462 I BooksSync: Finished books sync
,03-31 09:43:45.415  3520  3520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 09:43:45.415   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38241, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:43:45.418   822  1150 I ActivityManager: Killing 3054:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-31 09:43:45.422  3520  3520 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 09:43:45.434  3520  3520 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-31 09:43:45.446  1352  1373 I art     : Explicit concurrent mark sweep GC freed 17231(933KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 846us total 28.347ms
,03-31 09:43:45.528  3520  3520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-31 09:43:45.528  3520  3520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 09:43:45.544  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 09:43:45.545  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:45.545  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:45.545  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:45.549  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:45.585  3418  3468 E KeepSync: IOException
03-31 09:43:45.585  3418  3468 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 09:43:45.585  3418  3468 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 09:43:45.585  3418  3468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 09:43:45.585  3418  3468 E KeepSync: 	... 10 more
03-31 09:43:45.585  3418  3468 W KeepSync: Sync result 2
,03-31 09:43:45.589  3520  3595 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 09:43:45.592  3520  3520 D Atlas   : Validating map...
,03-31 09:43:45.597   822  1233 V WindowManager: Adding window Window{1fa52751 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (after Window{2622b760 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 09:43:45.597   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38241, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
03-31 09:43:45.598   822  1396 I ActivityManager: Killing 2792:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-31 09:43:45.807  3520  3578 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-31 09:43:45.818   822  1233 I ActivityManager: Killing 1437:android.process.acore/u0a5 (adj 15): empty #17
03-31 09:43:45.848  3520  3595 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 09:43:45.857  3520  3595 D OpenGLRenderer: Enabling debug mode 0
03-31 09:43:45.926   822   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s102ms
03-31 09:43:45.928  1235  1235 I Keyboard.Facilitator: onFinishInput()
03-31 09:43:45.943  3520  3520 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-31 09:43:45.945  3520  3520 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3520
03-31 09:43:46.021  3520  3520 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-31 09:43:46.119   822  1233 I ActivityManager: Start proc 3604:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
03-31 09:43:46.137   822  1233 I ActivityManager: Killing 2814:com.google.android.gm/u0a78 (adj 15): empty #17
03-31 09:43:46.148  3520  3596 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576311296
03-31 09:43:46.151  3520  3596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 09:43:46.151  3520  3596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 09:43:46.151  3520  3596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 09:43:46.151  3520  3596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 09:43:46.151  3520  3596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 09:43:46.151  3520  3596 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@232afb9f added. We now have 1 listener(s)
03-31 09:43:46.244   822  1397 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 09:43:46.246  3520  3596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-31 09:43:46.247  3520  3596 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-31 09:43:46.247  3520  3596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-31 09:43:46.248  3520  3596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 09:43:46.250  3520  3596 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31d3d34a added. We now have 1 listener(s)
03-31 09:43:46.250  3520  3596 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-31 09:43:46.254   822  1024 D WifiService: New client listening to asynchronous messages
03-31 09:43:46.255  3520  3596 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-31 09:43:46.258  3520  3596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 09:43:46.259  3520  3596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 09:43:46.259  3520  3596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 09:43:46.259  3520  3596 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-31 09:43:46.261  3520  3596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-31 09:43:46.261   822  1397 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-31 09:43:46.262  3520  3596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 09:43:46.267  3520  3596 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 09:43:46.267  3520  3596 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 09:43:46.267  3520  3596 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 09:43:46.269  3520  3596 I io.jxcore.node.LifeCycleMonitor: start: OK
03-31 09:43:46.270  3520  3520 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 09:43:46.271  3604  3604 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1459410226271
03-31 09:43:46.272  3520  3520 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-31 09:43:46.273  3604  3604 D         : TimeServiceNative: User Time to be set is 1459410226271
03-31 09:43:46.273  3604  3604 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-31 09:43:46.273  3604  3604 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-31 09:43:46.273  3604  3604 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1459410226271
03-31 09:43:46.273  3604  3604 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-31 09:43:46.273   373   880 D QC-time-services: Daemon: Connection accepted:time_genoff
03-31 09:43:46.273   373  3624 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1459410226271
03-31 09:43:46.273   373  3624 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1459410226271, operation = 0
03-31 09:43:46.273   373  3624 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/17/70 3:55:25
03-31 09:43:46.273   373  3624 D QC-time-services: Daemon:Value read from RTC seconds = 19713325000
03-31 09:43:46.273   373  3624 D QC-time-services: Daemon:new time 1459410226271 
03-31 09:43:46.273   373  3624 D QC-time-services: Daemon: delta 1439696901271 genoff 1439696901271 
03-31 09:43:46.274   373  3624 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901271 to memory
03-31 09:43:46.274   373  3624 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-31 09:43:46.274   373  3624 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-31 09:43:46.280   373  3624 D QC-time-services: Updating the TOD offset
03-31 09:43:46.280   373  3624 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696901271 to memory
03-31 09:43:46.280   373  3624 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-31 09:43:46.280   373  3624 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-31 09:43:46.284   373  3624 E QC-time-services: Daemon:Update to modem bit set
03-31 09:43:46.284   373  3624 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-31 09:43:46.284   373  3624 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1143445426271
03-31 09:43:46.285  3604  3604 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-31 09:43:46.290  3520  3520 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-31 09:43:46.352   373   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-31 09:43:46.358   373   877 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-31 09:43:46.368   822  1233 I ActivityManager: Start proc 3626:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
03-31 09:43:46.373   822  1150 I ActivityManager: Killing 1871:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
03-31 09:43:46.536  3626  3626 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-31 09:43:46.536  3626  3626 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 09:43:46.536  3626  3626 I GAv4    :   adb logcat -s GAv4
03-31 09:43:46.550  3626  3626 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-31 09:43:46.561  3626  3626 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-31 09:43:46.566  3626  3645 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-31 09:43:46.676  1771  1771 V Herrevad: NQAS connected
03-31 09:43:46.697   822  1024 D WifiService: New client listening to asynchronous messages
03-31 09:43:46.699  3156  3156 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 09:43:46.699  3156  3156 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 09:43:46.796  1352  1641 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-31 09:43:46.796  1352  1641 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:46.796  1352  1641 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:46.796  1352  1641 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-31 09:43:46.800  1352  1641 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:46.809  3156  3654 E Babel   : UserRecoverableAuthException.
03-31 09:43:46.810  3156  3654 E Babel   : eei: BadAuthentication
03-31 09:43:46.810  3156  3654 E Babel   : 	at eeg.a(Unknown Source)
03-31 09:43:46.810  3156  3654 E Babel   : 	at eeg.a(Unknown Source)
03-31 09:43:46.810  3156  3654 E Babel   : 	at eeg.a(Unknown Source)
03-31 09:43:46.810  3156  3654 E Babel   : 	at g.a(Unknown Source)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cae.a(SourceFile:3089)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-31 09:43:46.810  3156  3654 E Babel   : 	at crl.a(SourceFile:492)
03-31 09:43:46.810  3156  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cas.b(SourceFile:106)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cap.d(SourceFile:335)
03-31 09:43:46.810  3156  3654 E Babel   : 	at caq.run(SourceFile:81)
03-31 09:43:46.810  3156  3654 E Babel   : Error getting auth token
03-31 09:43:46.810  3156  3654 E Babel   : dvm
03-31 09:43:46.810  3156  3654 E Babel   : 	at g.a(Unknown Source)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cae.a(SourceFile:3089)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-31 09:43:46.810  3156  3654 E Babel   : 	at crl.a(SourceFile:492)
03-31 09:43:46.810  3156  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cas.b(SourceFile:106)
03-31 09:43:46.810  3156  3654 E Babel   : 	at cap.d(SourceFile:335)
03-31 09:43:46.810  3156  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-31 09:43:46.814  3156  3654 E Babel   : Account registration failed 1-Redacted-21
03-31 09:43:46.814  3156  3654 E Babel   : cyp: null -- null
03-31 09:43:46.814  3156  3654 E Babel   : 	at cae.a(SourceFile:3121)
03-31 09:43:46.814  3156  3654 E Babel   : 	at cae.a(SourceFile:1131)
03-31 09:43:46.814  3156  3654 E Babel   : 	at cws.a(SourceFile:4333)
03-31 09:43:46.814  3156  3654 E Babel   : 	at cws.a(SourceFile:1419)
03-31 09:43:46.814  3156  3654 E Babel   : 	at crl.a(SourceFile:492)
03-31 09:43:46.814  3156  3654 E Babel   : 	at crl.a(SourceFile:1468)
03-31 09:43:46.814  3156  3654 E Babel   : 	at cqu.a(SourceFile:4416)
03-31 09:43:46.814  3156  3654 E Babel   : 	at cas.b(SourceFile:106)
03-31 09:43:46.814  3156  3654 E Babel   : 	at cap.d(SourceFile:335)
03-31 09:43:46.814  3156  3654 E Babel   : 	at caq.run(SourceFile:81)
,03-31 09:43:46.826  3156  3654 I art     : Note: end time exceeds epoch: 
,03-31 09:43:46.839  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-31 09:43:46.839  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:46.839  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:46.839  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:46.842  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:46.854  1352  1369 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-31 09:43:46.870  3156  3660 E Babel   : Unexpected exception while authenticating.
03-31 09:43:46.870  3156  3660 E Babel   : eej: User intervention required. Notification has been pushed.
03-31 09:43:46.870  3156  3660 E Babel   : 	at eeg.b(Unknown Source)
03-31 09:43:46.870  3156  3660 E Babel   : 	at eeg.b(Unknown Source)
03-31 09:43:46.870  3156  3660 E Babel   : 	at g.a(Unknown Source)
03-31 09:43:46.870  3156  3660 E Babel   : 	at cae.b(SourceFile:1146)
03-31 09:43:46.870  3156  3660 E Babel   : 	at dcg.run(SourceFile:5617)
03-31 09:43:46.870  3156  3660 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:43:46.870  3156  3660 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:43:46.870  3156  3660 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-31 09:43:46.891  3520  3623 W jxcore-log: Initializing JXcore engine
03-31 09:43:46.891  3520  3623 W jxcore-log: JXcore engine is ready
,03-31 09:43:46.923  3623  3623 W Thread-375: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10024]" dev="sockfs" ino=10024 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-31 09:43:46.923  3623  3623 W Thread-375: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-31 09:43:46.923  3623  3623 W Thread-375: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10145]" dev="sockfs" ino=10145 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-31 09:43:46.923  3623  3623 W Thread-375: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21817]" dev="sockfs" ino=21817 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-31 09:43:46.942  3520  3623 W jxcore-log: Starting JXcore engine
,03-31 09:43:47.013  3520  3623 W jxcore-log: Platform android
03-31 09:43:47.013  3520  3623 W jxcore-log: 
03-31 09:43:47.013  3520  3623 W jxcore-log: Process ARCH arm
03-31 09:43:47.013  3520  3623 W jxcore-log: 
,03-31 09:43:47.203  3520  3623 I jxcore-log: JXcore Cordova bridge is ready!
03-31 09:43:47.203  3520  3623 I jxcore-log: 
03-31 09:43:47.203  3520  3623 W jxcore-log: JXcore engine is started
,03-31 09:43:47.212  3520  3596 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-31 09:43:47.216  3520  3520 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 09:43:47.568  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:47.681   822   837 I art     : Explicit concurrent mark sweep GC freed 18074(788KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.448ms total 80.578ms
,03-31 09:43:47.742  1352  3665 I VacuumService: Vacuum at: now=1459410227742 tag=VacuumService
,03-31 09:43:47.786  3293  3664 V GoogleAuthProtoRequest: [330] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:43:47.884  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 09:43:47.885  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:47.885  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:47.885  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:47.898  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:47.930  3293  3664 W ExperimentUpdateService: [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:43:47.932  3293  3664 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:43:48.112  1352  3666 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 09:43:48.144  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:48.684  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:48.876  1352  3666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 09:43:48.877  1352  3666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:43:48.877  1352  3666 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:48.877  1352  3666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:48.889  1352  3666 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 09:43:48.954  1352  3666 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 09:43:48.954  1352  3666 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 09:43:48.954  1352  3666 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 09:43:49.068  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:49.281  1352  3666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-31 09:43:49.281  1352  3666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:49.281  1352  3666 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:49.281  1352  3666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:49.287  1352  3666 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:49.325  1352  3666 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 09:43:49.325  1352  3666 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 09:43:49.325  1352  3666 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 09:43:49.471  3351  3459 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-31 09:43:49.494  1352  3666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 09:43:49.494  1352  3666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:43:49.494  1352  3666 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:49.494  1352  3666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:49.508  1352  3666 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:49.581  1352  3666 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 09:43:49.581  1352  3666 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 09:43:49.581  1352  3666 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 09:43:49.704  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:49.829  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:49.951  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:50.031  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:50.152  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:50.291  1352  3666 W Uploader:  no longer exists, so no auth token.
,03-31 09:43:50.424  1352  3666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-31 09:43:50.425  1352  3666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:50.425  1352  3666 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-31 09:43:50.425  1352  3666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:50.430  1352  3666 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:50.469  1352  3666 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 09:43:50.469  1352  3666 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-31 09:43:50.469  1352  3666 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-31 09:43:50.565  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:50.680  1352  3666 W Uploader: No account for auth token provided
,03-31 09:43:51.874   822  1397 I ActivityManager: Killing 2753:com.android.vending/u0a19 (adj 15): empty #17
,03-31 09:43:54.563   822   837 I ActivityManager: Start proc 3677:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-31 09:43:54.730  3677  3677 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-31 09:43:54.816  3677  3677 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-31 09:43:54.931   822  2114 I ActivityManager: Start proc 3713:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-31 09:43:54.958  3677  3677 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 09:43:54.959  3677  3677 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-31 09:43:54.965  3713  3713 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 09:43:54.965  3713  3713 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 09:43:54.991  3713  3713 I MultiDex: VM with version 2.1.0 has multidex support
03-31 09:43:54.991  3713  3713 I MultiDex: install
03-31 09:43:54.991  3713  3713 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 09:43:55.002   822  1196 I ActivityManager: Killing 2934:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-31 09:43:55.008  3677  3692 D Finsky  : [369] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-31 09:43:55.221  3677  3677 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 09:43:55.224  3677  3677 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-31 09:43:55.227  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.239  3677  3677 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-31 09:43:55.263  3713  3713 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 09:43:55.273  3677  3677 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-31 09:43:55.284  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 09:43:55.284  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:55.284  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:55.284  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:55.287  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.306  1352  3739 I art     : Explicit concurrent mark sweep GC freed 50050(2MB) AllocSpace objects, 4(369KB) LOS objects, 36% free, 27MB/43MB, paused 1.536ms total 36.812ms
,03-31 09:43:55.315  3677  3692 D Finsky  : [369] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-31 09:43:55.348  3713  3713 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 09:43:55.352  1352  2104 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 09:43:55.354  1352  1352 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 09:43:55.358  1771  1771 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 09:43:55.393   822   838 I ActivityManager: Start proc 3747:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-31 09:43:55.403  1771  3760 D LocationInitializer: Restart initialization of location
,03-31 09:43:55.426  3747  3747 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-31 09:43:55.426  3747  3747 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 09:43:55.454  3747  3747 I MultiDex: VM with version 2.1.0 has multidex support
03-31 09:43:55.454  3747  3747 I MultiDex: install
03-31 09:43:55.454  3747  3747 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 09:43:55.466  3747  3747 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-31 09:43:55.496  3747  3747 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 09:43:55.503  1352  2108 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-31 09:43:55.505  1352  1352 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 09:43:55.508  1771  1771 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: Install did not work
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: java.io.IOException: fcntl failed: EAGAIN (Try again)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at com.google.android.gms.common.app.a.run(SourceFile:136)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at libcore.io.Posix.fcntlFlock(Native Method)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
03-31 09:43:55.513  3747  3768 W NativeLibraryUtils: 	... 4 more
,03-31 09:43:55.516  3747  3747 D WearableService: callingUid 10011, callindPid: 3747
,03-31 09:43:55.528  1771  3769 D LocationInitializer: Restart initialization of location
,03-31 09:43:55.532  1802  2066 E MDM     : [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 09:43:55.535  1802  2066 E MDM     : [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-31 09:43:55.625  3677  3677 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-31 09:43:55.819  3677  3677 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-31 09:43:55.830  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.852  1352  1641 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 09:43:55.852  1352  1641 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:55.852  1352  1641 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:55.852  1352  1641 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:55.856  1352  1641 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.867  3677  3677 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 09:43:55.872  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.891  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-31 09:43:55.892  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:55.892  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:55.892  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:55.895  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.940  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.973  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 09:43:55.973  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:55.973  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:55.973  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:55.979  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:55.991   822   822 I art     : Explicit concurrent mark sweep GC freed 23922(1158KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.142ms total 50.225ms
,03-31 09:43:56.001  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 09:43:56.002  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
,03-31 09:43:56.004  3677  3677 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-31 09:43:56.031  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 09:43:56.031  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:43:56.031  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:56.031  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:56.035  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:56.047  3677  3677 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 09:43:56.167  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:56.203  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 09:43:56.203  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:43:56.203  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:43:56.204  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:43:56.209  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:43:56.222  3677  3677 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-31 09:43:56.225  3677  3677 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,03-31 09:43:56.231  3677  3677 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 09:43:56.233  3677  3677 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,03-31 09:43:56.247  1802  1819 D DeviceConnectionService: client connected with version: 7571000
,03-31 09:43:56.891  3520  3623 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 09:43:56.891  3520  3623 I jxcore-log: 
,03-31 09:43:56.894  3520  3623 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 09:43:56.894  3520  3623 I jxcore-log: 
,03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 09:43:56.902  3520  3623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 09:43:56.906  3520  3623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 09:43:56.908  3520  3623 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 09:43:56.908  3520  3623 I jxcore-log: 
,03-31 09:43:56.910  3520  3623 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 09:43:56.910  3520  3623 I jxcore-log: 
,03-31 09:43:57.424  3520  3623 I jxcore-log: Unit Test app is loaded
03-31 09:43:57.424  3520  3623 I jxcore-log: 
,03-31 09:43:57.429  3520  3623 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 09:43:57.429  3520  3623 I jxcore-log: 
,03-31 09:43:57.437  3520  3623 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 09:43:57.439  3520  3623 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 09:43:57.439  3520  3623 I jxcore-log: 
,03-31 09:43:57.441  3520  3623 I jxcore-log: My device name is: motorola-Nexus 6,
03-31 09:43:57.441  3520  3623 I jxcore-log: 
,03-31 09:43:57.448  3520  3520 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74),
,03-31 09:44:00.554   822  1150 I ActivityManager: Killing 3328:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-31 09:44:00.777   822  1150 I ActivityManager: Killing 3392:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-31 09:44:01.217  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 09:44:01.217  3520  3623 I jxcore-log: 
,03-31 09:44:01.598  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 09:44:01.598  3520  3623 I jxcore-log: 
,03-31 09:44:01.611  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,03-31 09:44:01.611  3520  3623 I jxcore-log: 
,03-31 09:44:01.616  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
,03-31 09:44:01.616  3520  3623 I jxcore-log: 
,03-31 09:44:01.654  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
,03-31 09:44:01.654  3520  3623 I jxcore-log: 
,03-31 09:44:01.671  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,03-31 09:44:01.671  3520  3623 I jxcore-log: 
,03-31 09:44:01.677  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
,03-31 09:44:01.677  3520  3623 I jxcore-log: 
,03-31 09:44:02.748  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:44:03.651  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 09:44:03.651  3520  3623 I jxcore-log: 
,03-31 09:44:03.668  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 09:44:03.668  3520  3623 I jxcore-log: 
,03-31 09:44:03.678  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 09:44:03.678  3520  3623 I jxcore-log: 
,03-31 09:44:03.924  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 09:44:03.924  3520  3623 I jxcore-log: 
,03-31 09:44:03.994  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 09:44:03.994  3520  3623 I jxcore-log: 
,03-31 09:44:04.048  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 09:44:04.048  3520  3623 I jxcore-log: 
,03-31 09:44:04.055  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 09:44:04.055  3520  3623 I jxcore-log: ,
,03-31 09:44:04.065  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 09:44:04.065  3520  3623 I jxcore-log: 
,03-31 09:44:04.070  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 09:44:04.070  3520  3623 I jxcore-log: 
,03-31 09:44:04.076  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 09:44:04.076  3520  3623 I jxcore-log: 
,03-31 09:44:04.091  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 09:44:04.091  3520  3623 I jxcore-log: 
,03-31 09:44:04.111  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 09:44:04.111  3520  3623 I jxcore-log: 
,03-31 09:44:04.193  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 09:44:04.193  3520  3623 I jxcore-log: ,
,03-31 09:44:04.198  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 09:44:04.198  3520  3623 I jxcore-log: 
,03-31 09:44:04.224  3520  3623 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 09:44:04.224  3520  3623 I jxcore-log: 
,03-31 09:44:04.505  3520  3623 I jxcore-log: Connected to the test server
03-31 09:44:04.505  3520  3623 I jxcore-log: 
,03-31 09:44:11.258  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:11.325  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 09:44:11.326  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:44:11.326  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:11.327  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:11.339  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:11.378  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 09:44:11.379  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 09:44:11.380  3677  3677 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 1.
,03-31 09:44:16.085  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 09:44:16.086  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:44:16.087  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.087  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.096  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:16.126  3094  3791 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 09:44:16.126  3094  3791 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at blb.a(PG:3937)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at czp.a(PG:18188)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at czp.a(PG:9087)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:44:16.126  3094  3791 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	... 12 more
03-31 09:44:16.126  3094  3791 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at fal.a(PG:38)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:44:16.126  3094  3791 E HttpOperation: 	... 14 more
,03-31 09:44:16.294  3418  3794 V KeepSync: Connecting to GoogleApiClient
,03-31 09:44:16.355  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 09:44:16.355  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:44:16.355  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.355  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.361  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:16.379  3094  3795 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 09:44:16.379  3094  3795 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at blb.a(PG:3937)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at czp.a(PG:18188)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:44:16.379  3094  3795 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	... 12 more
03-31 09:44:16.379  3094  3795 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at fal.a(PG:38)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:44:16.379  3094  3795 E HttpOperation: 	... 14 more
,03-31 09:44:16.399  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-31 09:44:16.399  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:44:16.399  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.399  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.404  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: Handling authorization failure
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 09:44:16.424  1771  3797 E ClientConnectionOperation: 	... 7 more
,03-31 09:44:16.427  3418  3794 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 09:44:16.433  3418  3794 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:44:16.438  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 09:44:16.438  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:44:16.438  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.439  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.443  3418  3794 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
03-31 09:44:16.444  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-31 09:44:16.446  3418  3794 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:44:16.458  3094  3795 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 09:44:16.458  3094  3795 E HttpOperation: java.io.IOException: Cannot obtain authentication token,
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at hec.a(PG:42)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at hee.a(PG:102)
,03-31 09:44:16.458  3094  3795 E HttpOperation: 	at czr.a(PG:65)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at kka.a(PG:108)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	,at czp.a(PG:19176)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:44:16.458  3094  3795 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jdj.a(PG:4091),
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	... 15 more
03-31 09:44:16.458  3094  3795 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:44:16.458  3094  3795 E HttpOperation: 	at fal.a(PG:38)
,03-31 09:44:16.458  3094  3795 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:44:16.458  3094  3795 E HttpOperation: 	... 17 more
03-31 09:44:16.459  3094  3795 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 09:44:16.459  3094  3795 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jdm.a(PG:82)
,03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at hec.a(PG:42)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	,at hee.a(PG:102)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at czr.a(PG:65)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at kka.a(PG:108)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at czp.a(PG:9081)
,03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jdm.a(PG:77)
,03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	... 15 more
03-31 09:44:16.459  3094  3795 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at fal.a(PG:38)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 09:44:16.459  3094  3795 E ExperimentLoader: 	... 17 more,
,03-31 09:44:16.519  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 09:44:16.520  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:44:16.521  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.521  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.526  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:16.557   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 168957, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:44:16.566  3418  3794 E KeepSync: IOException
03-31 09:44:16.566  3418  3794 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 09:44:16.566  3418  3794 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 09:44:16.566  3418  3794 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 09:44:16.566  3418  3794 E KeepSync: 	... 10 more
03-31 09:44:16.566  3418  3794 W KeepSync: Sync result 2
,03-31 09:44:16.584   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200706, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:44:16.595  3351  3799 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 09:44:16.609  3351  3800 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 09:44:16.643  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 09:44:16.643  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:44:16.643  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.643  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.649  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 09:44:16.683  1352  1373 I art     : Explicit concurrent mark sweep GC freed 42189(2MB) AllocSpace objects, 15(1653KB) LOS objects, 37% free, 26MB/42MB, paused 1.492ms total 30.722ms
,03-31 09:44:16.777  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 09:44:16.777  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:44:16.777  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:16.777  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:16.781  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:16.792  3351  3800 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 09:44:16.792  3351  3799 E BooksSync: Soft error
03-31 09:44:16.792  3351  3799 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:44:16.792  3351  3799 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:44:16.793  3351  3799 E BooksSync: Sync error
03-31 09:44:16.793  3351  3799 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:44:16.793  3351  3799 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:44:16.793  3351  3799 I BooksSync: Finished books sync
,03-31 09:44:16.798   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201330, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:44:28.547  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:44:31.447  3293  3806 V GoogleAuthProtoRequest: [332] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:44:31.496  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 09:44:31.497  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:44:31.497  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:31.497  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:31.500  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:44:31.513  3293  3806 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:44:31.579  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:31.602  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 09:44:31.602  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:44:31.602  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:31.603  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:31.608  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:31.628  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 09:44:31.628  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 09:44:31.629  3677  3677 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 2.
,03-31 09:44:45.933  1235  1497 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 09:44:45.933  1235  1497 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 09:44:45.957  1352  1352 I ConfigService: onCreate
,03-31 09:44:51.030  1352  1352 I ConfigService: onDestroy
,03-31 09:44:55.662   822  2114 I art     : Explicit concurrent mark sweep GC freed 33756(1501KB) AllocSpace objects, 8(505KB) LOS objects, 32% free, 33MB/49MB, paused 1.287ms total 85.274ms
,03-31 09:44:55.767  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:55.788  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 09:44:55.789  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:44:55.789  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:44:55.789  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:44:55.792  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:44:55.804  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
03-31 09:44:55.804  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 09:44:55.804  3677  3677 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,03-31 09:45:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:45:16.125  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 09:45:16.125  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:16.125  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:16.126  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:16.132  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 09:45:16.155  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:16.168  3094  3817 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 09:45:16.168  3094  3817 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at blb.a(PG:3937)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at czp.a(PG:18188)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:45:16.168  3094  3817 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	... 12 more
03-31 09:45:16.168  3094  3817 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at fal.a(PG:38)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:45:16.168  3094  3817 E HttpOperation: 	... 14 more
,03-31 09:45:16.219  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 09:45:16.219  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:16.219  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:16.219  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:16.225  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:16.247  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-31 09:45:16.248  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 09:45:16.248  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 09:45:16.248  3677  3677 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
03-31 09:45:16.248  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:16.248  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:16.248  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:16.253  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:16.276  3094  3817 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 09:45:16.276  3094  3817 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at hec.a(PG:42)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at hee.a(PG:102)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at czr.a(PG:65)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at kka.a(PG:108)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at czp.a(PG:19176)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:45:16.276  3094  3817 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	... 15 more
03-31 09:45:16.276  3094  3817 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at fal.a(PG:38)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:45:16.276  3094  3817 E HttpOperation: 	... 17 more
,03-31 09:45:16.278  3094  3817 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,03-31 09:45:16.278  3094  3817 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	,at jcs.o(PG:406)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: ,	at jcs.i(PG:143)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at hec.a(PG:42)
,03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at hee.a(PG:102)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at czr.a(PG:65),
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at kka.a(PG:108)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	,at czp.a(PG:19176)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: ,	at czp.a(PG:9081)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at czq.run(PG:1686),
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
,03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	... 15 more
03-31 09:45:16.278  3094  38,17 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at fal.a(PG:38)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 09:45:16.278  3094  3817 E ExperimentLoader: 	,... 17 more
,03-31 09:45:16.437   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 232977, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:45:28.706  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:45:36.516  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:36.612  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,03-31 09:45:36.613  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:45:36.613  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:36.614  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:36.626  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:36.670  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 09:45:36.671  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 09:45:36.672  3677  3677 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-31 09:45:46.025  3351  3824 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 09:45:46.044  3418  3823 V KeepSync: Connecting to GoogleApiClient
,03-31 09:45:46.070  3351  3825 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 09:45:46.143  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 09:45:46.143  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:46.143  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:46.143  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:46.150  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:46.167  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-31 09:45:46.168  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:46.168  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 09:45:46.168  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:46.181  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: Handling authorization failure
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 09:45:46.212  1771  3827 E ClientConnectionOperation: 	... 7 more
,03-31 09:45:46.217  3418  3823 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 09:45:46.221  3418  3823 E SQLiteLog: (284) automatic index on blob_node(is_deleted),
,03-31 09:45:46.238  3418  3823 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:45:46.240  3418  3823 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:45:46.275  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 09:45:46.275  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:46.275  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:46.275  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:46.279  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:46.297  3351  3825 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 09:45:46.298  3351  3824 E BooksSync: Soft error
03-31 09:45:46.298  3351  3824 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:45:46.298  3351  3824 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:45:46.298  3351  3824 E BooksSync: Sync error
03-31 09:45:46.298  3351  3824 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:45:46.298  3351  3824 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 09:45:46.299  3351  3824 I BooksSync: Finished books sync
,03-31 09:45:46.304   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 263865, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:45:46.318  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 09:45:46.318  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:46.319  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:46.319  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:46.324  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:46.381  3418  3823 E KeepSync: IOException
03-31 09:45:46.381  3418  3823 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
,03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 09:45:46.381  3418  3823 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 09:45:46.381  3418  3823 E KeepSync: 	,at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 09:45:46.381  3418  3823 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 09:45:46.381  3418  3823 E KeepSync: 	... 10 more
03-31 09:45:46.381  3418  3823 W KeepSync: Sync result 2
,03-31 09:45:46.393   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 262039, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:45:56.749  3293  3831 V GoogleAuthProtoRequest: [333] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:45:56.822  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 09:45:56.822  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:56.822  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:56.822  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:56.832  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:56.849  3293  3831 W ExperimentUpdateService: [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:45:56.850  3293  3831 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:45:56.961  1352  1352 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 09:45:57.023  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:57.062  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-31 09:45:57.062  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:45:57.062  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:45:57.062  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:45:57.125   822  1397 I art     : Explicit concurrent mark sweep GC freed 29981(1291KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.501ms total 79.883ms
,03-31 09:45:57.139  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:45:57.185  1352  1352 I art     : Explicit concurrent mark sweep GC freed 49511(2MB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 27MB/43MB, paused 990us total 46.976ms
,03-31 09:45:57.197  3677  3677 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-31 09:45:57.198  3677  3677 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-31 09:45:57.199  3677  3677 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,03-31 09:45:57.767  1352  3834 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,03-31 09:46:02.742  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:46:28.866  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:46:46.338  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 09:46:46.338  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:46:46.338  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:46:46.339  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:46:46.346  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:46:46.381  3094  3851 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 09:46:46.381  3094  3851 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at blb.a(PG:3937)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at czp.a(PG:18188)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:46:46.381  3094  3851 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	... 12 more
03-31 09:46:46.381  3094  3851 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at fal.a(PG:38)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:46:46.381  3094  3851 E HttpOperation: 	... 14 more
,03-31 09:46:46.445  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 09:46:46.445  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:46:46.445  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:46:46.445  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:46:46.451  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:46:46.463  3094  3851 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 09:46:46.463  3094  3851 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at hec.a(PG:42)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at hee.a(PG:102)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at czr.a(PG:65)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at kka.a(PG:108)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at czp.a(PG:19176)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:46:46.463  3094  3851 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	... 15 more
03-31 09:46:46.463  3094  3851 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at fal.a(PG:38)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:46:46.463  3094  3851 E HttpOperation: 	... 17 more
,03-31 09:46:46.465  3094  3851 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 09:46:46.465  3094  3851 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at hec.a(PG:42)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at hee.a(PG:102)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at czr.a(PG:65)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	,at kka.a(PG:108)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	... 15 more
03-31 09:46:46.465  3094  3851 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at fal.a(PG:38)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 09:46:46.465  3094  3851 E ExperimentLoader: 	... 17 more
,03-31 09:46:46.591   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 324514, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:46:56.818   822   838 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a2c1763}
,03-31 09:46:56.827   822  1023 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.00 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-31 09:46:58.527   822  1196 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2a2c1763}
,03-31 09:46:58.587   822  1252 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-31 09:46:58.666   872   872 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-31 09:46:58.667   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-31 09:46:58.708   872   872 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
03-31 09:46:58.708   872   872 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-31 09:46:59.691   872   872 I kickstart: STATUS: Received file 'm9kefs2'
03-31 09:46:59.692   872   872 I kickstart: STATUS: 950272 bytes transferred in 0.983169 seconds
03-31 09:46:59.692   872   872 I kickstart: STATUS: Successfully downloaded files from target 
03-31 09:46:59.692   872   872 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-31 09:46:59.695   872   872 I kickstart: STATUS: Sahara protocol completed
,03-31 09:47:02.740  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:47:29.026  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:47:47.960  3418  3864 V KeepSync: Connecting to GoogleApiClient
,03-31 09:47:48.128  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-31 09:47:48.129  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:47:48.130  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:47:48.130  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:47:48.147  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: Handling authorization failure
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 09:47:48.189  1771  3866 E ClientConnectionOperation: 	... 7 more
,03-31 09:47:48.196  3418  3864 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 09:47:48.202  3418  3864 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:47:48.219  3418  3864 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-31 09:47:48.219  3418  3864 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:47:48.290  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 09:47:48.290  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:47:48.290  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 09:47:48.291  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:47:48.297  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:47:48.348  3418  3864 E KeepSync: IOException
03-31 09:47:48.348  3418  3864 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 09:47:48.348  3418  3864 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 09:47:48.348  3418  3864 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 09:47:48.348  3418  3864 E KeepSync: 	... 10 more
03-31 09:47:48.348  3418  3864 W KeepSync: Sync result 2
,03-31 09:47:48.358   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 412540, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:47:56.905  3293  3869 V GoogleAuthProtoRequest: [334] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:47:57.004  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 09:47:57.007  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:47:57.007  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:47:57.007  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:47:57.017  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:47:57.035  3293  3869 W ExperimentUpdateService: [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:47:57.036  3293  3869 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:48:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:48:17.889  3351  3876 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 09:48:17.917  3351  3877 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 09:48:17.999  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 09:48:18.000  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:48:18.000  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:48:18.001  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:48:18.016  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:48:18.144  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 09:48:18.145  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:48:18.145  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 09:48:18.147  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:48:18.157  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:48:18.185  3351  3877 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 09:48:18.188  3351  3876 E BooksSync: Soft error
03-31 09:48:18.188  3351  3876 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:48:18.188  3351  3876 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:48:18.188  3351  3876 E BooksSync: Sync error
03-31 09:48:18.188  3351  3876 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:48:18.188  3351  3876 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:48:18.188  3351  3876 I BooksSync: Finished books sync
,03-31 09:48:18.195   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 415675, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:48:27.138  3293  3878 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:48:27.174  1352  1641 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 09:48:27.174  1352  1641 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:48:27.174  1352  1641 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 09:48:27.174  1352  1641 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:48:27.180  1352  1641 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-31 09:48:27.201  3293  3878 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:48:27.202  3293  3878 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:48:29.188  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:48:55.005  1352  1352 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:48:55.058  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-31 09:48:55.059  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:48:55.059  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:48:55.059  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:48:55.067  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:48:55.119  1352  1722 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-31 09:48:55.119  1352  1722 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-31 09:48:55.119  1352  1722 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-31 09:48:55.119  1352  1722 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-31 09:48:55.119  1352  1722 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-31 09:48:55.119  1352  1722 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-31 09:48:55.119  1352  1722 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 09:48:55.132  3677  3711 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-31 09:48:55.132  3677  3711 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-31 09:48:55.132  3677  3711 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-31 09:48:55.132  3677  3711 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-31 09:48:55.132  3677  3711 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-31 09:48:55.132  3677  3711 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-31 09:48:55.132  3677  3711 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-31 09:48:55.199  3677  3711 W System  : Ignoring header User-Agent because its value was null.
,03-31 09:48:57.333   822  1396 I art     : Explicit concurrent mark sweep GC freed 34582(1496KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 2.295ms total 74.501ms
,03-31 09:48:57.392  3293  3886 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:48:57.439  1352  3838 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 09:48:57.439  1352  3838 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:48:57.439  1352  3838 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:48:57.440  1352  3838 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:48:57.445  1352  3838 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:48:57.472  3293  3886 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:48:57.473  3293  3886 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:49:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:49:18.057  1352  3838 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 09:49:18.057  1352  3838 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:49:18.058  1352  3838 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:49:18.058  1352  3838 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:49:18.069  1352  3838 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:49:18.103  3094  3893 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 09:49:18.103  3094  3893 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at blb.a(PG:3937)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at czp.a(PG:18188)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:49:18.103  3094  3893 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	... 12 more
03-31 09:49:18.103  3094  3893 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at fal.a(PG:38)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:49:18.103  3094  3893 E HttpOperation: 	... 14 more
,03-31 09:49:18.185  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 09:49:18.185  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:49:18.185  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 09:49:18.186  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:49:18.199  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:49:18.237  3094  3893 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 09:49:18.237  3094  3893 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at hec.a(PG:42)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at hee.a(PG:102)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at czr.a(PG:65)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at kka.a(PG:108)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at czp.a(PG:19176)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:49:18.237  3094  3893 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	... 15 more
03-31 09:49:18.237  3094  3893 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at fal.a(PG:38)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:49:18.237  3094  3893 E HttpOperation: 	... 17 more
03-31 09:49:18.239  3094  3893 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 09:49:18.239  3094  3893 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at hec.a(PG:42)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at hee.a(PG:102)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at czr.a(PG:65)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at kka.a(PG:108)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	... 15 more
03-31 09:49:18.239  3094  3893 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at fal.a(PG:38)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 09:49:18.239  3094  3893 E ExperimentLoader: 	... 17 more
,03-31 09:49:18.382   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 477983, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:49:29.347  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:49:57.654  3293  3901 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:49:57.763  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 09:49:57.765  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:49:57.765  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:49:57.765  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:49:57.769  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:49:57.801  1352  1352 I art     : Explicit concurrent mark sweep GC freed 57554(3MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 882us total 28.115ms
,03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:49:57.808  3293  3901 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:50:02.734  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:50:29.506  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:51:02.752  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:51:29.667  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:51:51.224  3418  3921 V KeepSync: Connecting to GoogleApiClient
,03-31 09:51:51.331  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-31 09:51:51.332  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:51:51.332  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:51:51.332  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:51:51.343  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: Handling authorization failure
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 09:51:51.376  1771  3923 E ClientConnectionOperation: 	... 7 more
,03-31 09:51:51.381  3418  3921 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 09:51:51.388  3418  3921 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:51:51.405  3418  3921 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:51:51.408  3418  3921 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:51:51.478  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-31 09:51:51.478  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:51:51.478  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:51:51.478  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:51:51.485  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:51:51.550  3418  3921 E KeepSync: IOException
03-31 09:51:51.550  3418  3921 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 09:51:51.550  3418  3921 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 09:51:51.550  3418  3921 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 09:51:51.550  3418  3921 E KeepSync: 	... 10 more
03-31 09:51:51.550  3418  3921 W KeepSync: Sync result 2
,03-31 09:51:51.558   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 655889, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:51:57.822  3293  3927 V GoogleAuthProtoRequest: [338] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:51:57.933  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 09:51:57.934  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:51:57.934  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:51:57.934  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:51:57.946  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:51:57.984  3293  3927 W ExperimentUpdateService: [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:51:57.985  3293  3927 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:51:58.043  3293  3930 V GoogleAuthProtoRequest: [339] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:51:58.107  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 09:51:58.108  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:51:58.108  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:51:58.108  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:51:58.116  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:51:58.143  3293  3930 W ExperimentUpdateService: [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	,at com.a.a.a.k.a(SourceFile:117)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: ,	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:51:58.145  3293  3930 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110),
,03-31 09:52:29.828  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:52:51.381  3351  3940 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 09:52:51.414  3351  3941 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 09:52:51.494  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 09:52:51.495  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:52:51.495  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:52:51.495  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:52:51.508  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:52:51.648  1352  3838 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 09:52:51.648  1352  3838 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 09:52:51.648  1352  3838 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:52:51.648  1352  3838 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:52:51.657  1352  3838 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:52:51.681  3351  3941 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 09:52:51.684  3351  3940 E BooksSync: Soft error
03-31 09:52:51.684  3351  3940 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:52:51.684  3351  3940 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:52:51.684  3351  3940 E BooksSync: Sync error
03-31 09:52:51.684  3351  3940 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 09:52:51.684  3351  3940 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 09:52:51.685  3351  3940 I BooksSync: Finished books sync
,03-31 09:52:51.695   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 692174, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-31 09:53:29.987  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:53:51.617   822  1196 I art     : Explicit concurrent mark sweep GC freed 39382(1745KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 1.299ms total 57.572ms
,03-31 09:53:51.651  1352  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 09:53:51.651  1352  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:53:51.651  1352  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:53:51.651  1352  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:53:51.654  1352  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:53:51.663  3094  3953 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 09:53:51.663  3094  3953 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at blb.a(PG:3937)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at czp.a(PG:18188)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:53:51.663  3094  3953 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	... 12 more
03-31 09:53:51.663  3094  3953 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at fal.a(PG:38)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:53:51.663  3094  3953 E HttpOperation: 	... 14 more
,03-31 09:53:51.688  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-31 09:53:51.689  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:53:51.689  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:53:51.689  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:53:51.692  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:53:51.701  3094  3953 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 09:53:51.701  3094  3953 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jdm.a(PG:82)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jcs.o(PG:406)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jcn.a(PG:1379)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jcs.i(PG:143)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at hec.a(PG:42)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at hee.a(PG:102)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at czr.a(PG:65)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at kka.a(PG:108)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at czp.a(PG:19176)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at czp.a(PG:9081)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at czq.run(PG:1686)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:53:51.701  3094  3953 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jdj.a(PG:4091)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jdj.a(PG:1125)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jdm.a(PG:77)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	... 15 more
03-31 09:53:51.701  3094  3953 E HttpOperation: Caused by: faj: BadAuthentication
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at fal.a(PG:38)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	at jdj.a(PG:4089)
03-31 09:53:51.701  3094  3953 E HttpOperation: 	... 17 more
,03-31 09:53:51.702  3094  3953 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 09:53:51.702  3094  3953 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at hec.a(PG:42)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at hee.a(PG:102)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at czr.a(PG:65)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at kka.a(PG:108)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jdj.a(PG:1125)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	... 15 more
03-31 09:53:51.702  3094  3953 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at fal.a(PG:38)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 09:53:51.702  3094  3953 E ExperimentLoader: 	... 17 more
,03-31 09:53:51.789   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 756401, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 09:54:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:55:02.741  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:55:30.306  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:56:00.253  1771  3976 I EventLogService: Opted in for usage reporting
,03-31 09:56:00.254  1771  3976 I EventLogService: Aggregate from 1459409118145 (log), 1459409118145 (data)
,03-31 09:56:00.339  3293  3977 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 09:56:00.363  1771  3976 W EventLogAggregator: Unknown tag: snet_gcore
03-31 09:56:00.363  1771  3976 W EventLogAggregator: Unknown tag: snet_launch_service
,03-31 09:56:00.423  1352  3838 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-31 09:56:00.423  1352  3838 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:56:00.423  1352  3838 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:56:00.423  1352  3838 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:56:00.425  1771  3976 I ServiceDumpSys: dumping service [account]
,03-31 09:56:00.433  1352  3838 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:56:00.449  3293  3977 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 09:56:00.450  3293  3977 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 09:56:02.740  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:56:42.320  2149  2226 W bt-btm  : Stopping oneshot timer
,03-31 09:57:02.740  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:57:30.627  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:58:02.740  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:58:30.787  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:59:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:59:30.947  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 09:59:57.178  3418  4020 V KeepSync: Connecting to GoogleApiClient
,03-31 09:59:57.342  1352  3838 I art     : Explicit concurrent mark sweep GC freed 66706(3MB) AllocSpace objects, 9(993KB) LOS objects, 36% free, 27MB/43MB, paused 2.261ms total 76.138ms
,03-31 09:59:57.380  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,03-31 09:59:57.381  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:59:57.381  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 09:59:57.381  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:59:57.399  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: Handling authorization failure
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-31 09:59:57.420  1771  4022 E ClientConnectionOperation: 	... 7 more
,03-31 09:59:57.422  3418  4020 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-31 09:59:57.424  3418  4020 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:59:57.430  3418  4020 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:59:57.430  3418  4020 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-31 09:59:57.533  1352  1369 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-31 09:59:57.533  1352  1369 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 09:59:57.533  1352  1369 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 09:59:57.533  1352  1369 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 09:59:57.537  1352  1369 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 09:59:57.606  3418  4020 E KeepSync: IOException
03-31 09:59:57.606  3418  4020 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-31 09:59:57.606  3418  4020 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-31 09:59:57.606  3418  4020 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-31 09:59:57.606  3418  4020 E KeepSync: 	... 10 more
03-31 09:59:57.606  3418  4020 W KeepSync: Sync result 2
,03-31 09:59:57.614   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1141857, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:00:00.629  3293  4026 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 10:00:00.655  1352  3443 D GCM     : Message class com.google.f.a.a.i
,03-31 10:00:00.691  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 10:00:00.691  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:00:00.694  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:00:00.694  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:00:00.709  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:00:00.731  3293  4026 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 10:00:00.732  3293  4026 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 10:01:02.741  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:01:10.166  3351  4042 I BooksSync: Starting books sync for 61035162, extras: ade
,03-31 10:01:10.211  3351  4043 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-31 10:01:10.314  1352  2554 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-31 10:01:10.315  1352  2554 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:01:10.315  1352  2554 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:01:10.315  1352  2554 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:01:10.330  1352  2554 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:01:10.466  1352  1641 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-31 10:01:10.466  1352  1641 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:01:10.466  1352  1641 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:01:10.466  1352  1641 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:01:10.474  1352  1641 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:01:10.502  3351  4043 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-31 10:01:10.504  3351  4042 E BooksSync: Soft error
03-31 10:01:10.504  3351  4042 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 10:01:10.504  3351  4042 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-31 10:01:10.505  3351  4042 E BooksSync: Sync error
03-31 10:01:10.505  3351  4042 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-31 10:01:10.505  3351  4042 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-31 10:01:10.505  3351  4042 I BooksSync: Finished books sync
,03-31 10:01:10.519   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1214890, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:01:26.959   822   855 I UsageStatsService: User[0] Flushing usage stats to disk
,03-31 10:02:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-31 10:02:18.430   822   855 I art     : Explicit concurrent mark sweep GC freed 43589(2MB) AllocSpace objects, 11(364KB) LOS objects, 31% free, 34MB/50MB, paused 2.551ms total 59.120ms
,03-31 10:02:18.575  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 10:02:18.575  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:02:18.575  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:02:18.576  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:02:18.584  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:02:18.613  3094  4056 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-31 10:02:18.613  3094  4056 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jdm.a(PG:82)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jcs.o(PG:406)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jcn.a(PG:1379)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jcs.i(PG:143)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at blb.a(PG:3937)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at czp.a(PG:18188)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at czp.a(PG:9081)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at czq.run(PG:1686)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:02:18.613  3094  4056 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jdj.a(PG:4091)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jdj.a(PG:1125)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jdm.a(PG:77)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	... 12 more
03-31 10:02:18.613  3094  4056 E HttpOperation: Caused by: faj: BadAuthentication
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at fal.a(PG:38)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	at jdj.a(PG:4089)
03-31 10:02:18.613  3094  4056 E HttpOperation: 	... 14 more
,03-31 10:02:18.688  1352  1722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-31 10:02:18.688  1352  1722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-31 10:02:18.689  1352  1722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-31 10:02:18.689  1352  1722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:02:18.699  1352  1722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:02:18.735  3094  4056 E HttpOperation: [getmobileexperiments] Unexpected exception
03-31 10:02:18.735  3094  4056 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jdm.a(PG:82)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jcs.o(PG:406)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jcn.a(PG:1379)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jcs.i(PG:143)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at hec.a(PG:42)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at hee.a(PG:102)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at czr.a(PG:65)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at kka.a(PG:108)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at czp.a(PG:19176)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at czp.a(PG:9081)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at czq.run(PG:1686)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:02:18.735  3094  4056 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jdj.a(PG:4091)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jdj.a(PG:1125)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jdm.a(PG:77)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	... 15 more
03-31 10:02:18.735  3094  4056 E HttpOperation: Caused by: faj: BadAuthentication
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at fal.a(PG:38)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	at jdj.a(PG:4089)
03-31 10:02:18.735  3094  4056 E HttpOperation: 	... 17 more
03-31 10:02:18.736  3094  4056 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-31 10:02:18.736  3094  4056 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jdm.a(PG:82)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jcs.o(PG:406)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jcn.a(PG:1379)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jcs.i(PG:143)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at hec.a(PG:42)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at hee.a(PG:102)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at czr.a(PG:65)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at kka.a(PG:108)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at czp.a(PG:19176)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at czp.a(PG:9081)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at czq.run(PG:1686)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jdj.a(PG:4091)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jdm.a(PG:77)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	... 15 more
03-31 10:02:18.736  3094  4056 E ExperimentLoader: Caused by: faj: BadAuthentication
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at fal.a(PG:38)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	at jdj.a(PG:4089)
03-31 10:02:18.736  3094  4056 E ExperimentLoader: 	... 17 more
,03-31 10:02:18.858   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1283064, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,03-31 10:03:31.590  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:04:01.065  3293  4074 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-31 10:04:01.118  1352  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-31 10:04:01.118  1352  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-31 10:04:01.118  1352  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-31 10:04:01.119  1352  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-31 10:04:01.123  1352  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 10:04:01.136  3293  4074 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-31 10:04:01.137  3293  4074 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-31 10:04:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:04:31.746  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:05:02.740  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:05:31.906  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:06:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 10:07:02.739  2149  2217 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
