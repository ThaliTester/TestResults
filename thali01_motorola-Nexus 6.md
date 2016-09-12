#### Test 84843296543e137_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 13:40:19.190   873  2059 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,--------- beginning of system
09-12 13:40:19.426   873   885 I ActivityManager: Start proc 3804:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
09-12 13:40:19.496  3804  3804 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
09-12 13:40:19.548  3763  3816 V KeepSync: Connecting to GoogleApiClient
09-12 13:40:19.549   873  1702 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
09-12 13:40:19.579  3804  3804 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-12 13:40:19.587  3804  3804 I BooksApp: Created application version: 3.6.9 (30609)
09-12 13:40:19.591  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:40:19.593  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:40:19.620  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 13:40:19.621  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 13:40:19.621  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:19.621  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:40:19.636  1736  3821 V BaseAuthAsyncOperation: access token request failed
09-12 13:40:19.639  3763  3816 V KeepSync: GoogleApiClient failed to connect with error code: 4
09-12 13:40:19.697  3804  3823 I BooksSync: Starting books sync for 61035162, extras: ade
09-12 13:40:19.814  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 13:40:19.814  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-12 13:40:19.814  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:19.814  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:40:19.827  3804  3829 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
09-12 13:40:19.858  3763  3816 E KeepSync: IOException
09-12 13:40:19.858  3763  3816 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 13:40:19.858  3763  3816 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:40:19.858  3763  3816 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 13:40:19.858  3763  3816 E KeepSync: 	... 10 more
09-12 13:40:19.858  3763  3816 W KeepSync: Sync result 2
09-12 13:40:19.867   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 91192, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
09-12 13:40:19.884  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 13:40:19.884  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 13:40:19.884  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:19.884  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:40:19.927  3802  3802 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 13:40:19.931  3802  3802 D AndroidRuntime: CheckJNI is OFF
09-12 13:40:19.931  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 13:40:19.931  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 13:40:19.931  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:19.931  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:40:19.947  3804  3829 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:40:19.948  3804  3823 E BooksSync: Soft error
09-12 13:40:19.948  3804  3823 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:40:19.948  3804  3823 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 13:40:19.949  3804  3823 E BooksSync: Sync error
09-12 13:40:19.949  3804  3823 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:40:19.949  3804  3823 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 13:40:19.949  3804  3823 I BooksSync: Finished books sync
09-12 13:40:19.953   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 91916, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
09-12 13:40:19.956   873  2233 I ActivityManager: Killing 3445:com.google.android.apps.photos/u0a71 (adj 15): empty #17
09-12 13:40:19.967  3802  3802 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 13:40:20.006  3802  3802 I Radio-JNI: register_android_hardware_Radio DONE
09-12 13:40:20.024  3802  3802 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 13:40:20.030   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 13:40:20.100  2012  3751 W SearchService: Abort, client detached.
09-12 13:40:20.106  2012  2351 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b5ab790
09-12 13:40:20.106  2012  2361 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 13:40:20.106  2012  2012 I HotwordDetector: Closing mic
09-12 13:40:20.135  3802  3802 D AndroidRuntime: Shutting down VM
09-12 13:40:20.157   873  1420 I ActivityManager: Start proc 3837:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 13:40:20.181   377  2365 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 13:40:20.183   377  2365 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 13:40:20.190   377  1237 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 13:40:20.193  2012  2360 I MicroRecognitionRnrImpl: Detection finished
09-12 13:40:20.193  2012  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 13:40:20.257  3837  3837 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 13:40:20.284  3837  3837 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 13:40:20.290  3837  3837 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1469-1471)
09-12 13:40:20.290  3837  3837 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:40:20.311  3837  3837 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ea75b63}
09-12 13:40:20.311  3837  3837 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:40:20.311  3837  3837 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:40:20.317  3837  3837 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 13:40:20.318  3837  3837 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:40:20.381  3837  3837 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 13:40:20.398  3837  3837 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 13:40:20.398  3837  3837 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:40:20.398  3837  3837 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:40:20.398  3837  3837 I Adreno  : Build Date                       : 10/20/15
09-12 13:40:20.398  3837  3837 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:40:20.398  3837  3837 I Adreno  : Local Branch                     : M14
09-12 13:40:20.398  3837  3837 I Adreno  : Remote Branch                    : 
09-12 13:40:20.398  3837  3837 I Adreno  : Remote Branch                    : 
09-12 13:40:20.398  3837  3837 I Adreno  : Reconstruct Branch               : 
,09-12 13:40:20.461   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7892063:true
,09-12 13:40:20.545  3837  3837 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 13:40:20.558  3837  3837 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 13:40:20.615  3837  3875 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 13:40:20.628  3837  3862 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 13:40:20.663  3837  3875 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:40:20.735   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +600ms
,09-12 13:40:20.753  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-12 13:40:20.820  3837  3837 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3837
,09-12 13:40:20.965  3837  3837 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:40:20.978   873  2225 I ActivityManager: Killing 3240:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 13:40:21.030   873  2225 I ActivityManager: Killing 2740:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-12 13:40:21.128  3837  3877 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680934608
,09-12 13:40:21.135  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:40:21.135  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:40:21.135  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:40:21.135  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:40:21.135  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 13:40:21.135  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5951876 added. We now have 1 listener(s)
,09-12 13:40:21.140  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61,
,09-12 13:40:21.141  3837  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:40:21.142  3837  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:40:21.142  3837  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 13:40:21.149  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9031b4d added. We now have 1 listener(s)
09-12 13:40:21.150  3837  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:40:21.154   873  1316 D WifiService: New client listening to asynchronous messages
,09-12 13:40:21.155  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:40:21.156  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 13:40:21.156  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 13:40:21.156  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-12 13:40:21.156  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-12 13:40:21.160  3837  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:40:21.160  3837  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 13:40:21.168  3837  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:21.168  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:40:21.168  3837  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 13:40:21.168  3837  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:40:21.169  3837  3877 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:40:21.171  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:21.174  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:21.202  3837  3837 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:40:22.153  3837  3887 W jxcore-log: Initializing JXcore engine
,09-12 13:40:22.153  3837  3887 W jxcore-log: JXcore engine is ready
,09-12 13:40:22.187  3887  3887 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8973 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-12 13:40:22.187  3887  3887 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10586]" dev="sockfs" ino=10586 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-12 13:40:22.187  3887  3887 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 13:40:22.190  3887  3887 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25419]" dev="sockfs" ino=25419 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 13:40:22.202  3837  3887 W jxcore-log: Starting JXcore engine
,09-12 13:40:22.284  3837  3887 W jxcore-log: Platform android
09-12 13:40:22.284  3837  3887 W jxcore-log: 
09-12 13:40:22.284  3837  3887 W jxcore-log: Process ARCH arm
09-12 13:40:22.284  3837  3887 W jxcore-log: 
,09-12 13:40:22.490  3837  3887 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:40:22.490  3837  3887 I jxcore-log: 
,09-12 13:40:22.491  3837  3887 W jxcore-log: JXcore engine is started
,09-12 13:40:22.510  3837  3877 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:40:22.515  3837  3837 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:40:22.978   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 13:40:24.583  3804  3820 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-12 13:40:29.687  3549  3562 D Finsky  : [273] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-12 13:40:29.704  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:29.716  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:29.718  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:29.770  1507  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 13:40:29.770  1507  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-12 13:40:29.770  1507  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:29.770  1507  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:40:29.788  3549  3562 D Finsky  : [273] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-12 13:40:30.415  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:30.440  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 13:40:30.440  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 13:40:30.440  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:40:30.440  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:40:30.453  3549  3549 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 13:40:30.453  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:40:30.453  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-12 13:40:36.864  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 13:40:36.864  3837  3887 I jxcore-log: 
,09-12 13:40:36.867  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 13:40:36.867  3837  3887 I jxcore-log: 
,09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:36.878  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:40:36.887  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:40:36.894  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:40:36.894  3837  3887 I jxcore-log: 
,09-12 13:40:36.903  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:40:36.903  3837  3887 I jxcore-log: 
,09-12 13:40:37.284  3837  3887 I jxcore-log: Running unit tests
09-12 13:40:37.284  3837  3887 I jxcore-log: 
,09-12 13:40:37.285  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:40:37.285  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e848304 added. We now have 2 listener(s)
,09-12 13:40:37.286  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:40:37.286  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:40:37.286  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:40:37.286  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:40:37.287  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76f30ed added. We now have 2 listener(s)
09-12 13:40:37.287  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:40:37.287  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:40:37.290  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:37.308  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:40:37.312  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-12 13:40:37.312  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:40:37.313  3837  3887 D executeNativeTests: Running unit tests
,09-12 13:40:37.322  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:37.329  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:37.379  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:40:37.379  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 added. We now have 3 listener(s),
09-12 13:40:37.380  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:40:37.380  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:40:37.380  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:40:37.380  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:40:37.380  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 added. We now have 3 listener(s)
09-12 13:40:37.380  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:40:37.381  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:40:37.384  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:37.397  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:40:37.402  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:40:37.403  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:40:37.405  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 13:40:37.405  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:40:37.405  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:40:37.405  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:40:37.407  3837  3887 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 13:40:37.407  3837  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:40:37.407  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:40:37.407  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:40:37.407  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:40:37.407  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:40:37.408  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:37.408  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:37.408  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:37.409  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:37.409  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:40:37.409  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.409  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:40:37.409  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:40:37.409  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 removed from the list
09-12 13:40:37.409  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:37.410  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 removed from the list
09-12 13:40:37.418  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:40:37.419  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:40:37.420  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.423  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.423  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.426  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:37.426  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:37.427  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:37.427  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:37.434  3837  3887 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 13:40:37.437  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:37.437  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:37.437  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:37.438  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:37.438  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.438  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.439  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:37.439  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:37.440  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:37.440  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:37.440  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.441  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.441  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.441  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.444  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:37.444  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:37.444  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:37.444  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:37.450  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:40:37.450  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:40:37.451  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:40:37.452  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:40:37.453  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:40:37.453  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:40:37.453  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:40:37.453  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:40:37.453  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:37.453  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:37.453  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:37.454  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:37.454  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.454  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.454  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:37.454  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:37.454  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:37.454  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:37.454  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.454  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.454  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:37.455  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:37.456  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:37.456  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:37.457  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:37.457  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:37.457  3837  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:40:37.461  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:37.469  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:40:37.472  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:37.472  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:40:37.473  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:40:37.474  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:40:37.474  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:40:37.475  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:40:37.475  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:40:37.475  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:40:37.477  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:40:37.482  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:40:37.482  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:40:37.493  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:40:37.499  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:40:37.500  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:40:37.506  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 13:40:37.511  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 13:40:37.512  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:40:37.512  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:40:37.513  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:40:37.514  3837  3887 D BluetoothAdapter: STATE_ON
09-12 13:40:37.531  2536  2549 D BtGatt.GattService: registerClient() - UUID=3365fd66-a561-4248-8031-51c42ce4eaa0
,09-12 13:40:37.534  2536  2556 D BtGatt.GattService: onClientRegistered() - UUID=3365fd66-a561-4248-8031-51c42ce4eaa0, clientIf=5
,09-12 13:40:37.535  3837  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:40:37.537  2536  2579 D BtGatt.GattService: start scan with filters
,09-12 13:40:37.542  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:40:37.543  2536  2559 D BtGatt.ScanManager: handling starting scan
,09-12 13:40:37.543  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:40:37.544  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:40:37.544  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:40:37.549  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:40:37.549  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:40:37.550  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:40:37.551  2536  2559 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:40:37.553  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:40:37.558  3837  3887 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:40:37.567  2536  2556 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:40:37.567  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:37.569  2536  2559 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:40:37.585  2536  2556 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:40:37.585  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:37.586  2536  2559 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:40:37.587  2536  2559 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:40:37.611  2536  2556 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:40:37.611  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:37.626  2536  2556 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
09-12 13:40:37.626  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:37.696   873  2059 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 13:40:38.052  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 13:40:38.052  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:40:38.053  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:40:39.131  2536  2536 D BtGatt.ScanManager: awakened up at time 140312
,09-12 13:40:39.137  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:39.179  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-12 13:40:39.179  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:39.180  2536  2556 D BtGatt.GattService: current time is 140361479252
,09-12 13:40:39.181  2536  2556 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -100, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -85, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -99, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 13:40:39.185  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 13:40:39.188  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 13:40:39.188  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 13:40:39.189  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 13:40:39.190  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:40:39.191  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 13:40:40.683  2536  2536 D BtGatt.ScanManager: awakened up at time 141864
,09-12 13:40:40.686  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:40.697  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:40:40.697  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:42.200  2536  2536 D BtGatt.ScanManager: awakened up at time 143381
,09-12 13:40:42.204  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:42.219  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-12 13:40:42.219  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:42.219  2536  2556 D BtGatt.GattService: current time is 143400809537
,09-12 13:40:42.219  2536  2556 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 13:40:42.220  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-12 13:40:42.220  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 13:40:42.220  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-12 13:40:42.221  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 13:40:42.567  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:40:42.568  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:40:42.569  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:40:42.569  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:42.570  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:40:42.571  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:40:42.571  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:40:42.571  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:40:42.571  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:40:42.573  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:40:42.574  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:40:42.578  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:40:42.584  2536  2579 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:40:42.586  2536  2550 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:40:42.588  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:40:42.588  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:40:42.588  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:40:42.589  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:40:42.589  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:40:42.593  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:40:42.594  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:40:42.594  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:40:42.595  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:40:42.597  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:40:42.601  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:40:42.601  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:42.601  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:42.601  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:40:42.601  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:40:42.601  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:40:42.602  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
,09-12 13:40:42.603  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:42.603  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:40:42.603  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:42.603  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:42.607  2536  2556 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:40:42.607  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:42.608  2536  2559 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:40:42.622  2536  2556 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:40:42.622  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:42.623  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:42.633  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 13:40:42.634  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:43.103  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:40:47.604  3837  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:40:47.611  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:47.625  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:40:47.632  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:40:47.633  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:40:47.634  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:40:47.634  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:40:47.634  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 13:40:47.634  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:40:47.635  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:40:47.640  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:40:47.644  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:40:47.645  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:40:47.645  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:47.661  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:40:47.663  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:40:47.664  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:40:47.672  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:40:47.673  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:40:47.673  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:40:47.675  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:40:47.681  2536  2549 D BtGatt.GattService: registerClient() - UUID=bd93f991-2292-41cd-b0f9-5bee0fe0c2d4
,09-12 13:40:47.682  2536  2556 D BtGatt.GattService: onClientRegistered() - UUID=bd93f991-2292-41cd-b0f9-5bee0fe0c2d4, clientIf=5
,09-12 13:40:47.685  3837  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:40:47.696  2536  2579 D BtGatt.GattService: start scan with filters
,09-12 13:40:47.705  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:40:47.705  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:40:47.705  2536  2559 D BtGatt.ScanManager: handling starting scan
,09-12 13:40:47.706  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:40:47.706  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:40:47.717  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:40:47.718  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:40:47.718  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:40:47.726  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:40:47.728  2536  2556 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 13:40:47.729  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.729  3837  3887 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:40:47.729  2536  2559 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:40:47.736  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:40:47.736  3837  3887 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:40:47.736  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:40:47.736  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:40:47.736  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:47.736  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-12 13:40:47.736  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:40:47.736  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:40:47.736  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:40:47.736  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:40:47.737  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:40:47.737  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:40:47.738  3837  3887 D BluetoothAdapter: STATE_ON
09-12 13:40:47.739  2536  2548 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:40:47.743  2536  2580 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:40:47.743  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:40:47.743  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:40:47.744  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:40:47.744  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:40:47.744  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,09-12 13:40:47.745  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:40:47.745  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:40:47.745  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:40:47.746  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:40:47.746  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:40:47.747  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:40:47.747  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:40:47.748  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:40:47.748  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:47.748  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:47.748  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:40:47.748  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:47.748  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:47.748  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:47.748  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:40:47.748  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:47.749  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:47.749  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-12 13:40:47.754  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:47.754  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:40:47.754  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:47.754  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:47.754  2536  2556 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:40:47.755  3837  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:40:47.755  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.756  2536  2559 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:40:47.756  2536  2559 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:40:47.757  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:40:47.767  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:40:47.769  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:40:47.770  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:40:47.770  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:40:47.772  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:47.771  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:40:47.772  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 13:40:47.773  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:40:47.773  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:40:47.776  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:40:47.777  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:40:47.777  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:40:47.781  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:40:47.782  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:40:47.782  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:40:47.782  2536  2556 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 13:40:47.783  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.786  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:40:47.786  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:40:47.786  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:40:47.787  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:40:47.789  2536  2556 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 13:40:47.789  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.790  2536  2580 D BtGatt.GattService: registerClient() - UUID=cf30b684-adb3-443e-8a98-16226e7db87c
,09-12 13:40:47.790  2536  2556 D BtGatt.GattService: onClientRegistered() - UUID=cf30b684-adb3-443e-8a98-16226e7db87c, clientIf=5
,09-12 13:40:47.791  3837  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:40:47.791  2536  2579 D BtGatt.GattService: start scan with filters
,09-12 13:40:47.794  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:40:47.794  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:40:47.794  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:40:47.794  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:40:47.796  2536  2556 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:40:47.797  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:47.797  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:40:47.797  2536  2559 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:40:47.797  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:40:47.797  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:40:47.799  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:40:47.801  3837  3887 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:40:47.804  2536  2556 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 13:40:47.804  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:47.804  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:47.809  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 13:40:47.809  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.811  2536  2559 D BtGatt.ScanManager: handling starting scan
,09-12 13:40:47.817  2536  2556 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 13:40:47.817  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:47.817  2536  2559 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:40:47.823  2536  2556 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:40:47.823  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.823  2536  2559 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:40:47.823  2536  2559 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:40:47.841  2536  2556 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:40:47.841  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:47.849  2536  2556 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:40:47.850  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:48.298  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 13:40:48.299  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:40:48.299  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:40:49.357  2536  2536 D BtGatt.ScanManager: awakened up at time 150538
,09-12 13:40:49.359  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:49.411  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 13:40:49.411  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:49.412  2536  2556 D BtGatt.GattService: current time is 150593200166
,09-12 13:40:49.413  2536  2556 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -102, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -102, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 13:40:49.414  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-12 13:40:49.415  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-12 13:40:49.416  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-12 13:40:49.416  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 13:40:49.417  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 13:40:49.418  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:40:50.927  2536  2536 D BtGatt.ScanManager: awakened up at time 152108
,09-12 13:40:50.940  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:50.981  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 13:40:50.981  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:51.205  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:51.217  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:51.222  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:40:51.271  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 13:40:51.272  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 13:40:51.272  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:40:51.273  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:40:51.319  3549  3549 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 13:40:51.320  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 13:40:51.321  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 13:40:51.712   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 13:40:51.722  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-12 13:40:51.735   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:40:51.735   873   893 I Adreno  : Build Date                       : 10/20/15
09-12 13:40:51.735   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:40:51.735   873   893 I Adreno  : Local Branch                     : M14
09-12 13:40:51.735   873   893 I Adreno  : Remote Branch                    : 
09-12 13:40:51.735   873   893 I Adreno  : Remote Branch                    : 
09-12 13:40:51.735   873   893 I Adreno  : Reconstruct Branch               : 
,09-12 13:40:51.789   283   308 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (284 us)
,09-12 13:40:52.431  3837  3837 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:40:52.432  3837  3837 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 13:40:52.505   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 13:40:52.508  3837  3837 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7ccb951 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c9ba9cd, 16908290=android.view.AbsSavedState$1@c9ba9cd}, android:focusedViewId=100}]}]
09-12 13:40:52.508  3837  3837 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 13:40:52.510  3837  3837 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:40:52.510  3837  3837 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 13:40:52.514  2536  2536 D BtGatt.ScanManager: awakened up at time 153695
,09-12 13:40:52.515  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:52.517   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 13:40:52.520   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-12 13:40:52.521   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 13:40:52.521   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 13:40:52.534  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 13:40:52.534  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:52.534  2536  2556 D BtGatt.GattService: current time is 153715312873
,09-12 13:40:52.534  2536  2556 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -102, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-12 13:40:52.534  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 13:40:52.534  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 13:40:52.534  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-12 13:40:52.535  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 13:40:52.535  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-12 13:40:52.535  2536  2556 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:40:52.591   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 13:40:52.661  1507  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:40:52.661  1507  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 13:40:52.661  1507  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:52.661  1507  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:40:52.689  3593  3906 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 13:40:52.689  3593  3906 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at blb.a(PG:3937)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at czp.a(PG:18188)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:40:52.689  3593  3906 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	... 12 more
09-12 13:40:52.689  3593  3906 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at fal.a(PG:38)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:40:52.689  3593  3906 E HttpOperation: 	... 14 more
,09-12 13:40:52.737  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:40:52.737  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 13:40:52.737  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:40:52.737  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:40:52.769   283   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 13:40:52.770   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 13:40:52.770   873  1341 D SurfaceControl: Excessive delay in setPowerMode(): 250ms
,09-12 13:40:52.779   873   893 I DreamManagerService: Entering dreamland.
09-12 13:40:52.780   873   893 I PowerManagerService: Dozing...
09-12 13:40:52.780  3593  3906 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 13:40:52.780  3593  3906 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at hec.a(PG:42)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at hee.a(PG:102)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at czr.a(PG:65)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at kka.a(PG:108)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at czp.a(PG:19176)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:40:52.780  3593  3906 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	... 15 more
09-12 13:40:52.780  3593  3906 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at fal.a(PG:38)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:40:52.780  3593  3906 E HttpOperation: 	... 17 more
,09-12 13:40:52.780   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
09-12 13:40:52.781  3593  3906 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 13:40:52.781  3593  3906 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at hec.a(PG:42)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at hee.a(PG:102)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at czr.a(PG:65)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at kka.a(PG:108)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588),
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	... 15 more
09-12 13:40:52.781  3593  3906 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	,at fal.a(PG:38)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 13:40:52.781  3593  3906 E ExperimentLoader: 	... 17 more
,09-12 13:40:52.802  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:40:52.802  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:52.802  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:40:52.802  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:52.802  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:40:52.802  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:40:52.802  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:40:52.802  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:40:52.802  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:40:52.803  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:40:52.803  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:40:52.803  3837  3887 D BluetoothAdapter: STATE_ON
09-12 13:40:52.804  2536  2550 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:40:52.804  2536  2549 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:40:52.805  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:40:52.805  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:40:52.805  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:40:52.805  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:40:52.805  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:40:52.806  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-12 13:40:52.806  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:40:52.806  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:40:52.806  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:40:52.807  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:40:52.808  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:40:52.808  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:40:52.808  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:40:52.810  2536  2556 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:40:52.810  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:52.810  2536  2559 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:40:52.816  2536  2556 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:40:52.816  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:40:52.817  2536  2559 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:40:52.822  2536  2556 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 13:40:52.822  2536  2556 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:40:52.822   377  1324 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-12 13:40:52.822   377  1324 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 13:40:52.832  1934  3909 D NfcService: Discovery configuration equal, not updating.
,09-12 13:40:52.834   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:40:52.840   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-12 13:40:52.844   873  1315 E native  : do suspend false
,09-12 13:40:52.858   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:40:52.871   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:40:52.875   873  1315 E native  : do suspend true
,09-12 13:40:52.875   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 153537, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:40:52.958   377  1239 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-12 13:40:52.959   377  1239 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 13:40:53.309  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:40:53.309  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:40:53.310  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:40:53.337   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-12 13:40:57.809  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:40:57.810  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.810  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:40:57.811  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.812  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:57.812  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:40:57.812  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.813  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.813  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.813  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:40:57.814  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.815  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.816  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.819  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:40:57.820  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.820  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.820  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.822  3837  3887 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 13:40:57.824  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:40:57.825  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:40:57.825  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:40:57.827  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:40:57.827  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.827  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.828  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
,09-12 13:40:57.828  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.828  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.828  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.828  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.828  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.828  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.828  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.829  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.829  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.829  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.829  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:40:57.831  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:40:57.831  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.831  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.831  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:57.831  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:40:57.831  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.832  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.832  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.832  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.832  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.832  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:40:57.832  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.833  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.833  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.833  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.834  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.834  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.834  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.834  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.835  3837  3887 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:40:57.835  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.835  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.835  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:57.836  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.836  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:57.836  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.836  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.836  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.836  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.836  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.836  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.836  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.836  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.836  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.838  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.838  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.838  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.838  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.839  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-12 13:40:57.839  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.839  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.839  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:40:57.839  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.839  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:57.839  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.840  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.840  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.840  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.840  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.840  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.840  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.840  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.840  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.841  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.841  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.841  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.841  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.842  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:40:57.842  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:40:57.842  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:40:57.842  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:40:57.843  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:40:57.843  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:40:57.843  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:40:57.843  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:40:57.843  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:40:57.843  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.843  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.843  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:40:57.844  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.844  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.844  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.844  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.844  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.844  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:40:57.844  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.844  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.844  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.844  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.844  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.846  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.846  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.846  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.846  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.847  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:40:57.847  3837  3887 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:40:57.847  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:40:57.851  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 13:40:57.851  3837  3887 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:40:57.851  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
09-12 13:40:57.851  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:40:57.851  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:40:57.851  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:40:57.852  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-12 13:40:57.853  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:40:57.854  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:40:57.854  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:40:57.854  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:40:57.854  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:40:57.854  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:40:57.854  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:40:57.854  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:40:57.855  3837  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-12 13:40:57.855  3837  3887 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:40:57.855  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:40:57.855  3837  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:40:57.855  3837  3887 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:40:57.855  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:40:57.855  3837  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:40:57.855  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:40:57.858  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 13:40:57.860  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-12 13:40:57.860  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 13:40:57.860  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 13:40:57.860  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:40:57.861  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:40:57.861  3837  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:40:57.861  3837  3887 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:40:57.861  3837  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-12 13:40:57.862  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:40:57.862  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.862  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:57.862  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.862  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.863  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.863  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:40:57.864  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.864  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.864  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.864  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:40:57.864  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.864  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.864  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.864  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.865  3837  3914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:40:57.865  3837  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-12 13:40:57.865  3837  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
09-12 13:40:57.865  3837  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
09-12 13:40:57.866  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:40:57.866  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.866  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.866  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.867  3837  3887 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:40:57.868  3837  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-12 13:40:57.869  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.869  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.869  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:57.869  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:40:57.869  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.869  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.869  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.869  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.870  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.870  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.870  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.870  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.870  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.870  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.871  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.871  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.871  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.871  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.872  3837  3887 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:40:57.873  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.873  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.873  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:40:57.873  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.873  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.873  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.873  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.873  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.873  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.873  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.873  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.873  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:40:57.873  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.874  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.874  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.875  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.875  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.875  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:40:57.876  3837  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-12 13:40:57.876  3837  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:40:57.876  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:40:57.876  3837  3887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:40:57.876  3837  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:40:57.876  3837  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:40:57.876  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:40:57.876  3837  3887 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:40:57.876  3837  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:40:57.877  3837  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:40:57.877  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 13:40:57.877  3837  3887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:40:57.877  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:40:57.877  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:40:57.877  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:40:57.877  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.877  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.877  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.877  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.877  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.877  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.877  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.878  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.878  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.878  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.878  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.879  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:40:57.879  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:40:57.879  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:40:57.879  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.880  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:40:57.881  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:40:57.881  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:40:57.881  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:40:57.881  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:40:57.881  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:40:57.881  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:40:57.881  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:40:57.881  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.882  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.883  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:41:02.883  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:41:02.883  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.884  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.884  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:41:02.884  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:41:02.885  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:41:02.885  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:41:02.886  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:41:02.886  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.886  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.887  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:41:02.887  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.887  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:41:02.887  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:02.888  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:02.888  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.888  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.889  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.892  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:41:02.892  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:41:02.893  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.893  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:41:02.898  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-12 13:41:02.900  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:41:02.902  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:41:02.904  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:41:02.905  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:41:02.906  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 13:41:02.906  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:41:02.906  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:41:02.907  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:41:02.907  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 13:41:02.907  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:41:02.908  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 13:41:02.908  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.908  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:41:02.909  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:41:02.909  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-12 13:41:02.909  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.909  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:41:02.909  3837  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
09-12 13:41:02.909  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:41:02.909  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-12 13:41:02.910  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.910  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.913  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:41:02.913  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:41:02.913  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:41:02.914  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:41:02.914  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:41:02.915  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:41:02.915  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:41:02.915  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-12 13:41:02.915  3837  3916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-12 13:41:02.916  3837  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:41:02.916  3837  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:41:02.916  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:41:02.916  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:02.917  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.917  3837  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-12 13:41:02.917  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
,09-12 13:41:02.917  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:41:02.918  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list,
,09-12 13:41:02.918  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:02.918  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.918  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.919  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.919  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.921  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:41:02.921  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:41:02.922  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.922  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:41:02.925  3837  3887 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 13:41:02.926  3837  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 13:41:02.926  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:41:02.926  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:41:02.926  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:41:02.927  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:41:02.927  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:41:02.927  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:41:02.927  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:41:02.927  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.927  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.927  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:41:02.927  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.928  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:41:02.928  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:02.928  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.928  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.928  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.928  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.929  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:41:02.929  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:41:02.929  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:41:02.929  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:41:02.937  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:41:02.938  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:41:02.938  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:41:02.938  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:41:02.938  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.938  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.939  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
,09-12 13:41:02.939  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.939  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:41:02.939  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:02.939  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:02.940  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.940  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:02.940  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.942  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:41:02.942  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:41:02.942  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:02.942  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:41:02.945  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:41:02.946  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:41:02.946  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:41:02.946  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:41:02.946  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:02.946  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.947  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4a75a3 not in the list
09-12 13:41:02.947  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:41:02.947  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
09-12 13:41:02.947  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:41:02.947  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.947  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:02.947  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:02.947  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:02.948  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:41:02.948  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:41:02.948  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:41:02.948  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df0a0 not in the list
,09-12 13:41:02.949  3837  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 13:41:02.950  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:41:02.950  3837  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 13:41:02.950  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:41:02.950  3837  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:41:02.950  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:41:02.953  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:41:02.953  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 13:41:02.954  3837  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:41:02.954  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:41:02.954  3837  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:41:02.954  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:41:02.954  3837  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:41:02.954  3837  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 13:41:02.955  3837  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-12 13:41:02.955  3837  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 13:41:02.955  3837  3887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:41:02.955  3837  3887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:41:02.955  3837  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:41:02.955  3837  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 13:41:02.956  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:41:02.957  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1940d93 added. We now have 3 listener(s)
,09-12 13:41:02.957  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:41:02.959  3837  3887 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 13:41:02.959   873  2227 D WifiService: setWifiEnabled: true pid=3837, uid=10000
09-12 13:41:02.959   873  2227 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:41:02.993   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-12 13:41:02.999  2536  2567 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-12 13:41:03.000  2536  2569 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-12 13:41:03.414  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:41:07.968  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:41:07.968  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@adec1d0 added. We now have 4 listener(s)
,09-12 13:41:07.969  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:41:07.986  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:07.986  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@adec1d0 removed from the list
09-12 13:41:07.986  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:41:07.987  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:07.987  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:41:07.990  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:41:07.990  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c615c9 added. We now have 4 listener(s)
09-12 13:41:07.990  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:41:07.995  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:07.996  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c615c9 removed from the list
09-12 13:41:07.996  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:41:07.996  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:07.996  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:07.999  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:41:07.999  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f70b4ce added. We now have 4 listener(s)
09-12 13:41:08.000  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:41:08.006   873  2225 D WifiService: setWifiEnabled: false pid=3837, uid=10000
09-12 13:41:08.007   873  2225 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:41:08.021  2536  2552 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 13:41:08.022  2536  2552 D BluetoothAdapterProperties: Setting state to 13
09-12 13:41:08.022  2536  2552 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 13:41:08.025  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:41:08.025  2536  2552 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:41:08.033  2536  2552 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:41:08.036  2536  2556 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:41:08.037  2536  2552 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-12 13:41:08.038  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:08.040  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:41:08.041  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.041  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:41:08.042  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:41:08.042  2536  2536 D BluetoothMapService: onReceive
09-12 13:41:08.042  2536  2536 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:41:08.042  2536  2536 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:41:08.042  2536  2536 D BluetoothMapService: MAP Service closeService in
09-12 13:41:08.043  2536  2536 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 13:41:08.043  2536  2536 D ObexServerSockets0: shutdown(block = true)
09-12 13:41:08.043  2536  2536 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:41:08.043  2536  2536 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 13:41:08.044  2536  2569 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 13:41:08.044  2536  2581 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 13:41:08.045  2536  2582 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 13:41:08.046  2536  2536 I BtOppRfcommListener: stopping Accept Thread
09-12 13:41:08.046  2536  3443 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:41:08.046  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 13:41:08.046  2536  3443 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:41:08.048  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 13:41:08.049   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:41:08.049   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-12 13:41:08.049   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:41:08.049   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:08.051  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:08.055   873  1315 E native  : do suspend true
,09-12 13:41:08.055  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:08.055  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:41:08.056  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.056  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:41:08.059  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:08.059  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:41:08.060  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.060  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:08.062  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:08.064   873   886 I ActivityManager: Start proc 3920:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 13:41:08.065   873  2061 D DhcpClient: Clearing IP address
09-12 13:41:08.065   373   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:41:08.067  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:08.068   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:08.069  2536  2536 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:41:08.070   873  2103 D DhcpClient: Receive thread stopped
,09-12 13:41:08.071  1360  2049 D BluetoothHeadset: Proxy object disconnected
,09-12 13:41:08.071  1360  1360 D HeadsetProfile: Bluetooth service disconnected
,09-12 13:41:08.071  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:08.071   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:08.071   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 13:41:08.072  1949  1962 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:08.072  1507  2637 V NativeCrypto: Read error: ssl=0xaa23d000: I/O error during system call, Connection timed out
,09-12 13:41:08.072   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 13:41:08.073  2536  2536 D A2dpService: Received stop request...Stopping profile...
,09-12 13:41:08.073  1507  2637 V NativeCrypto: SSL shutdown failed: ssl=0xaa23d000: I/O error during system call, Broken pipe
09-12 13:41:08.074  2536  2574 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:41:08.075  1360  1360 D BluetoothA2dp: Proxy object disconnected
,09-12 13:41:08.075   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 13:41:08.075   873  1703 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-12 13:41:08.075   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 13:41:08.075   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-12 13:41:08.076   873  2058 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-12 13:41:08.078  2536  2536 D HidService: Received stop request...Stopping profile...
,09-12 13:41:08.078  2536  2536 D HidService: Stopping Bluetooth HidService
09-12 13:41:08.079   404   404 E Parcel  : Reading a NULL string not supported here.
,09-12 13:41:08.079  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:08.079  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:41:08.080  1360  1360 D BluetoothInputDevice: Proxy object disconnected
09-12 13:41:08.080  1360  1360 D HidProfile: Bluetooth service disconnected
09-12 13:41:08.080  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.080  2536  2536 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:08.080  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:08.081   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 13:41:08.081   873  2058 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-12 13:41:08.081   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:41:08.081   873  1315 E native  : do suspend true
09-12 13:41:08.083  2536  2536 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:08.083  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.083  2536  2536 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:08.084   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 13:41:08.084  2536  2536 D HealthService: Received stop request...Stopping profile...
09-12 13:41:08.087  2536  2536 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:41:08.087  2536  2536 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:41:08.088  2536  2567 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:08.088  2536  2567 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:08.088  2536  2567 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:08.088  2536  2536 D PanService: Received stop request...Stopping profile...
09-12 13:41:08.089  2536  2556 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:41:08.089  2536  2556 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 13:41:08.090  2536  2536 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:08.090  2536  2536 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:08.090  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.090  2536  2536 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:08.091  2536  2556 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 13:41:08.091  2536  2567 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:08.091  2536  2567 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:08.091  2536  2567 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:41:08.091  2536  2567 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregist,ration
09-12 13:41:08.091  2536  2567 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:41:08.091  2536  2567 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:41:08.091  2536  2536 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:08.091  2536  2536 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:08.091  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.092  2536  2536 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:08.092  2536  2536 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:41:08.092  2536  2556 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 13:41:08.092  2536  2536 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:41:08.093  2536  2536 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:41:08.093  2536  2536 D BluetoothMapService: stop()
09-12 13:41:08.095  2536  2536 D BluetoothMapAppObserver: deinitObservers()
09-12 13:41:08.096  2536  2536 D BluetoothMapAppObserver: removeReceiver()
09-12 13:41:08.098  2536  2536 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:08.098  2536  2536 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:08.098  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.098  2536  2536 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:08.098  2536  2536 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:41:08.098  2536  2556 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 13:41:08.099  2536  2536 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:41:08.099  2536  2536 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:08.099  2536  2536 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:08.099  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.103  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:41:08.103  1360  1360 D PanProfile: Bluetooth service disconnected
09-12 13:41:08.103  1360  1360 D BluetoothMap: Proxy object disconnected
09-12 13:41:08.103  1360  1360 D MapProfile: Bluetooth service disconnected
09-12 13:41:08.099  2536  2536 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:08.103  2536  2536 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 13:41:08.104  2536  2536 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:41:08.105  2536  2536 D BluetoothMapService: MAP Service closeService in
09-12 13:41:08.105  2536  2536 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:08.105  2536  2536 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:08.105  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.105  2536  2536 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:08.105  2536  2552 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 13:41:08.105  2536  2552 D BluetoothAdapterProperties: Setting state to 15
09-12 13:41:08.105  2536  2552 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:41:08.106  2536  2552 I BluetoothAdapterState: Entering BleOnState
09-12 13:41:08.106  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:41:08.107   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:41:08.107  1360  2049 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:41:08.107  1360  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:08.108   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:08.108  1949  1962 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:08.108   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:08.108  1360  1372 D BluetoothPan: onBluetoothStateChange on: false,
09-12 13:41:08.109  2536  2536 D BluetoothMapService: cleanup()
09-12 13:41:08.109  2536  2536 D BluetoothMapService: MAP Service closeService in
09-12 13:41:08.111   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:08.111  1360  2049 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:41:08.111  1360  1384 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:41:08.112  2536  2552 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 13:41:08.112  2536  2552 D BluetoothAdapterProperties: Setting state to 16
,09-12 13:41:08.112  2536  2552 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 13:41:08.113  2536  2552 D BluetoothAdapterProperties: onBleDisable
09-12 13:41:08.113  2536  2552 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:41:08.113  2536  2553 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:41:08.114  2536  2556 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:41:08.115  2536  2567 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-12 13:41:08.115  2536  2567 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:08.116  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:08.116  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
09-12 13:41:08.117  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.117  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:08.119  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:08.119  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:08.120  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.120  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:08.121  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:08.121  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:08.122  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:08.124  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:08.124  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:08.129   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:08.154   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:08.154   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:41:08.155   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 13:41:08.155   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:41:08.155  3920  3920 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 13:41:08.157   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:41:08.158   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:41:08.162  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:08.163  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:08.164  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:08.164  3464  3464 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f338e77 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 13:41:08.173   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:41:08.176  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:08.176  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:08.176   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:41:08.176  2026  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:41:08.176  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.176  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:08.178  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:08.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:08.179  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.179  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:08.181  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:08.181  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:08.181  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:08.181  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:08.182  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:41:08.188   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b379a0d:true
09-12 13:41:08.188  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:08.201   873  1990 I ActivityManager: Start proc 3940:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 13:41:08.224   373   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 13:41:08.225   873  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 13:41:08.225   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:41:08.231  3920  3920 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 13:41:08.233  3920  3920 D BluetoothMap: Create BluetoothMap proxy object
,09-12 13:41:08.240  3940  3940 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 13:41:08.242  3920  3920 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 13:41:08.251  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:41:08.265   873  2233 I ActivityManager: Killing 3008:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 13:41:08.316  2536  2556 I bt_hci  : shut_down
,09-12 13:41:08.317  2536  2560 D bt_hwcfg: hw_epilog_process
,09-12 13:41:08.318  2536  2560 I bt_vendor: low_power_mode_cb
,09-12 13:41:08.340  2536  2560 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:41:08.340  2536  2560 I bt_vendor: epilog_cb
09-12 13:41:08.340  2536  2560 I bt_hci  : epilog_finished_callback
,09-12 13:41:08.347  2536  2556 I bt_hci_h4: hal_close
,09-12 13:41:08.348  2536  2556 I bt_userial_vendor: device fd = 51 close
,09-12 13:41:08.414  3940  3940 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.414  3940  3940 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.414  3940  3940 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.414  3940  3940 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.414  3940  3940 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.414  3940  3940 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.414  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.415  3940  3940 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.415  3940  3940 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:41:08.415  3940  3940 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:41:08.434  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:41:08.446  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:08.465  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:41:08.471  2536  2553 D bt_stack_manager: event_shut_down_stack finished.
,09-12 13:41:08.472  2536  2552 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 13:41:08.474   873  1994 I ActivityManager: Killing 3464:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 13:41:08.529  2536  2552 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 13:41:08.529  2536  2536 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:41:08.543  2536  2536 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:41:08.543  2536  2536 D BtGatt.GattService: stop()
09-12 13:41:08.543  2536  2536 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:41:08.546  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:41:08.547  2536  2536 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:08.547  2536  2536 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:41:08.547  2536  2536 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:08.547  2536  2536 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 13:41:08.548  2536  2552 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 13:41:08.548  2536  2552 D BluetoothAdapterProperties: Setting state to 10
09-12 13:41:08.548  2536  2552 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 13:41:08.548  2536  2552 I BluetoothAdapterState: Entering OffState
,09-12 13:41:08.550   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 13:41:08.552  1736  1736 D SystemUpdateService: onCreate
,09-12 13:41:08.563  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:41:08.571  2536  2536 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 13:41:08.571  2536  2536 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:41:08.571  2536  2536 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:41:08.572  2536  2553 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:41:08.576  2536  2553 D bt_stack_manager: event_clean_up_stack finished.
,09-12 13:41:08.581  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:41:08.584  1736  2615 I iu.UploadsManager: num queued entries: 0
,09-12 13:41:08.585  1736  2615 I iu.UploadsManager: num updated entries: 0
,09-12 13:41:08.588  2536  2536 I art     : System.exit called, status: 0
,09-12 13:41:08.588  2536  2536 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:41:08.604  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:41:08.605  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:41:08.606  1736  3972 I SystemUpdateService: active receiver: enabled
,09-12 13:41:08.613  1736  2615 I iu.SyncManager: NEXT; no task
,09-12 13:41:08.622  1736  3972 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:41:08.624  1736  3972 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-12 13:41:08.625  1736  3972 I SystemUpdateService: now status is 0 (complete)
09-12 13:41:08.625  1736  3972 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 13:41:08.625  1736  3972 I SystemUpdateService: file has been verified
09-12 13:41:08.625  1736  3972 I SystemUpdateService: OTA package size = 12249756
,09-12 13:41:08.631   873  1704 I ActivityManager: Start proc 3975:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 13:41:08.638  1736  3972 I SystemUpdateService: showing system update notification
,09-12 13:41:08.643   873   884 I ActivityManager: Process com.android.bluetooth (pid 2536) has died
,09-12 13:41:08.668  1736  1736 D SystemUpdateService: onDestroy
,09-12 13:41:08.687  3975  3975 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 13:41:08.690  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:41:08.713  3975  3975 D SprintDMHelper: simOperator: 
09-12 13:41:08.713  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:41:08.738   873  2233 I ActivityManager: Start proc 3988:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-12 13:41:08.739   873  2233 I ActivityManager: Killing 1707:android.process.acore/u0a5 (adj 15): empty #17
,09-12 13:41:08.768  3940  3959 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 13:41:08.778   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cb70358:true
,09-12 13:41:08.956   873  1703 I ActivityManager: Start proc 4004:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 13:41:08.958  3094  4003 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 13:41:08.991  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 13:41:09.043  4004  4004 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 13:41:09.043  4004  4004 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 13:41:09.043  4004  4004 I GAv4    :   adb logcat -s GAv4
,09-12 13:41:09.059  4004  4004 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:41:09.065  4004  4004 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:41:09.098  4004  4021 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:41:09.202  4004  4004 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 13:41:09.251  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 13:41:09.258  4004  4004 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 436-439)
,09-12 13:41:09.258  4004  4004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:41:09.273  4004  4004 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {66f0367}
,09-12 13:41:09.274  4004  4004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:41:09.274  4004  4004 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 13:41:09.283  4004  4004 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 13:41:09.285  4004  4004 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:41:09.301  4004  4004 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 13:41:09.315  4004  4004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 13:41:09.315  4004  4004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 13:41:09.315  4004  4004 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:41:09.315  4004  4004 I Adreno  : Build Date                       : 10/20/15
09-12 13:41:09.315  4004  4004 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:41:09.315  4004  4004 I Adreno  : Local Branch                     : M14
09-12 13:41:09.315  4004  4004 I Adreno  : Remote Branch                    : 
09-12 13:41:09.315  4004  4004 I Adreno  : Remote Branch                    : 
09-12 13:41:09.315  4004  4004 I Adreno  : Reconstruct Branch               : 
,09-12 13:41:09.380  4004  4004 I NSApplication: Starting up...
,09-12 13:41:09.387  4004  4050 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 13:41:09.421   873  1703 I ActivityManager: Start proc 4055:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 13:41:09.425   873  1703 I ActivityManager: Killing 3655:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 13:41:09.491  4055  4055 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 13:41:09.681   873   883 I ActivityManager: Killing 3671:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 13:41:09.776   873  2233 I ActivityManager: Start proc 4069:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 13:41:09.840  4069  4069 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 13:41:09.897  4069  4069 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 13:41:09.956   873  1994 I ActivityManager: Killing 2210:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 13:41:12.110   873   882 I art     : Background partial concurrent mark sweep GC freed 33049(1886KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.370ms total 103.013ms
,09-12 13:41:12.222  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:12.235  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:12.240  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:12.291  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 13:41:12.292  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 13:41:12.292  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:41:12.293  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:12.343  3549  3549 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 13:41:12.343  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:41:12.344  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-12 13:41:13.045   873  1420 D WifiService: setWifiEnabled: true pid=3837, uid=10000,
09-12 13:41:13.045   873  1420 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:41:13.064   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:41:13.067  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:13.067  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:13.067  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:13.067  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:13.069  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:13.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:13.069  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:13.069  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:13.070  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:13.070  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:13.070  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:13.070  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:13.086   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,09-12 13:41:13.087   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 13:41:13.088   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 13:41:13.089   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 13:41:13.089   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:41:13.090   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 13:41:13.090   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:41:13.107   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:41:13.107   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 13:41:13.108   373   871 D CommandListener: Setting iface cfg
09-12 13:41:13.108   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 13:41:13.108   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:41:13.117   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:41:13.117   873  1315 E native  : do suspend true
09-12 13:41:13.118   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:41:13.141   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:41:13.957   873  1994 I ActivityManager: Killing 3487:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-12 13:41:14.313   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:41:14.402   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.06 rxSuccessRate=7.44 delta 1000 -> 1000
,09-12 13:41:14.403   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 13:41:14.403   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:14.423   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:41:14.472   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:41:14.473  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:41:14.968  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:41:15.083  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:41:15.084  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:41:15.095   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:41:15.112   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:41:15.112   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:41:15.112   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:41:15.132   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:15.148   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:15.150   873  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 13:41:15.169   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:41:15.198   873  4105 D DhcpClient: Receive thread started
,09-12 13:41:15.289   873  1315 E native  : do suspend false
,09-12 13:41:15.313   873  2061 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:41:15.346   873  4105 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,09-12 13:41:15.347   873  2061 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,09-12 13:41:15.351   873  2061 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:41:15.391   873  4105 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:41:15.392   873  2061 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:41:15.397   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:15.408   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:41:15.409   873  2061 D DhcpClient: Scheduling renewal in 86399s
,09-12 13:41:15.410   873  1315 E native  : do suspend true
,09-12 13:41:15.440   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:41:15.444   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:41:15.447   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 13:41:15.450   873  1317 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 13:41:15.464   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:41:15.510   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 13:41:15.511   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 13:41:15.514   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 13:41:15.518   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 13:41:15.523   873  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 13:41:15.535   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 13:41:15.540   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 13:41:15.541   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 13:41:15.541   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 13:41:15.542   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 13:41:15.542   873  1317 D ConnectivityService:    accepting network in place of null
,09-12 13:41:15.542   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:41:15.545   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:41:15.593   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:15.629   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:15.635   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 13:41:15.636   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:41:15.640   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 13:41:15.647   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:41:15.654  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:15.655  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:41:15.655  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:15.655  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:15.661  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:15.661  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:41:15.661  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:15.661  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:41:15.665  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:15.666  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:41:15.666  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:15.666  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:41:15.673  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:41:15.683  1736  1736 D SystemUpdateService: onCreate
,09-12 13:41:15.687  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:41:15.707  1736  4115 I SystemUpdateService: active receiver: enabled
,09-12 13:41:15.722  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:41:15.730  1736  4118 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 13:41:15.730  1736  4118 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 13:41:15.732  1736  4118 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 13:41:15.733  1736  4115 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:41:15.738  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:41:15.739  1736  2615 I iu.UploadsManager: num queued entries: 0
,09-12 13:41:15.740  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:41:15.742  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:41:15.747  3975  3975 D SprintDMHelper: simOperator: 
,09-12 13:41:15.747  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:41:15.748  1736  4115 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 13:41:15.748  1736  4115 I SystemUpdateService: now status is 0 (complete)
09-12 13:41:15.749  1736  4115 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:41:15.749  1736  4115 I SystemUpdateService: file has been verified
,09-12 13:41:15.750  1736  4115 I SystemUpdateService: OTA package size = 12249756
,09-12 13:41:15.750  1736  2615 I iu.UploadsManager: num updated entries: 0
,09-12 13:41:15.753  1736  2615 I iu.SyncManager: NEXT; no task
,09-12 13:41:15.758  1736  4115 I SystemUpdateService: showing system update notification
,09-12 13:41:15.796  1507  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 13:41:15.796  1507  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 13:41:15.798  1507  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:15.799  1507  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:15.814  1736  1736 D SystemUpdateService: onDestroy
,09-12 13:41:15.830  1736  4118 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-12 13:41:16.161   873  4104 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177342, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:41:16.541   873  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:41:16.636   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 13:41:17.161  3094  4122 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:41:17.263   873  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:41:17 GMT], X-Android-Received-Millis=[1473680477261], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473680477157]}
,09-12 13:41:17.266   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:41:17.268   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-12 13:41:17.269   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 13:41:17.274   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:41:18.052   873  2225 D WifiService: setWifiEnabled: false pid=3837, uid=10000
,09-12 13:41:18.052   873  2225 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:41:18.096  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 13:41:18.104   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:41:18.104   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 13:41:18.105   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:41:18.105   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:18.128   873  1315 E native  : do suspend true
,09-12 13:41:18.144   873  2061 D DhcpClient: Clearing IP address
,09-12 13:41:18.146   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:18.149   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:41:18.151  1507  4127 V NativeCrypto: Read error: ssl=0x9ae91600: I/O error during system call, Connection timed out
,09-12 13:41:18.153  1507  4127 V NativeCrypto: SSL shutdown failed: ssl=0x9ae91600: I/O error during system call, Broken pipe
,09-12 13:41:18.154   873  4105 D DhcpClient: Receive thread stopped
09-12 13:41:18.157   873  1990 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-12 13:41:18.158   873  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-12 13:41:18.160   873  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:41:18.168   873  4103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-12 13:41:18.169   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-12 13:41:18.169   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 13:41:18.171   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:41:18.176   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 13:41:18.176   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 13:41:18.177   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 13:41:18.178   404   404 E Parcel  : Reading a NULL string not supported here.
,09-12 13:41:18.179   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:41:18.179   873  1315 E native  : do suspend true
,09-12 13:41:18.183   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 13:41:18.211   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:18.237   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:18.237   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:41:18.237   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 13:41:18.238   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:41:18.240   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 13:41:18.246  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:18.249  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:18.249  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.249  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:18.253  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:18.253  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:18.254  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.254  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:18.256  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:18.256  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:18.256  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:18.256  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:18.263  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:41:18.267  1736  1736 D SystemUpdateService: onCreate
,09-12 13:41:18.272  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:41:18.280  1736  4138 I SystemUpdateService: active receiver: enabled
,09-12 13:41:18.284  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:41:18.287  1736  2615 I iu.UploadsManager: num queued entries: 0
,09-12 13:41:18.293  1736  4138 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:41:18.295  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:41:18.297  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:41:18.298  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:41:18.302  3975  3975 D SprintDMHelper: simOperator: 
,09-12 13:41:18.303  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:41:18.287  1736  2615 I iu.UploadsManager: num updated entries: 0
,09-12 13:41:18.324   373   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 13:41:18.325   873  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 13:41:18.326   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:41:18.327   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:41:18.332  3094  4142 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 13:41:18.334  1736  4138 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 13:41:18.334  1736  4138 I SystemUpdateService: now status is 0 (complete)
09-12 13:41:18.334  1736  4138 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:41:18.334  1736  4138 I SystemUpdateService: file has been verified
,09-12 13:41:18.338  1736  2615 I iu.SyncManager: NEXT; no task
,09-12 13:41:18.334  1736  4138 I SystemUpdateService: OTA package size = 12249756
,09-12 13:41:18.342   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 13:41:18.347   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 13:41:18.350  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:18.350  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:18.350  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.350  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:18.352  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:18.353  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:18.353  2026  2337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:41:18.353  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.353  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:18.355  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:18.355  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:18.355  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:18.356  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:18.366  1736  4138 I SystemUpdateService: showing system update notification
,09-12 13:41:18.377  1736  1736 D SystemUpdateService: onDestroy
,09-12 13:41:22.969  2026  2739 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 13:41:23.109   873   890 I ActivityManager: Start proc 4145:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:41:23.237  4145  4145 D AdapterServiceConfig: Adding HeadsetService
09-12 13:41:23.237  4145  4145 D AdapterServiceConfig: Adding A2dpService
09-12 13:41:23.237  4145  4145 D AdapterServiceConfig: Adding HidService
09-12 13:41:23.237  4145  4145 D AdapterServiceConfig: Adding HealthService
09-12 13:41:23.237  4145  4145 D AdapterServiceConfig: Adding PanService
09-12 13:41:23.238  4145  4145 D AdapterServiceConfig: Adding GattService
09-12 13:41:23.238  4145  4145 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:41:23.250  4145  4145 D BluetoothAdapterState: make() - Creating AdapterState
09-12 13:41:23.250   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc91cc1:true
,09-12 13:41:23.254  4145  4145 I bt_bluedroid: init
,09-12 13:41:23.255  4145  4157 I BluetoothAdapterState: Entering OffState
,09-12 13:41:23.257  4145  4158 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 13:41:23.258  4145  4158 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:41:23.258  4145  4158 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 13:41:23.258  4145  4158 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 13:41:23.259  4145  4145 I bt_bluedroid: get_profile_interface socket
09-12 13:41:23.260  4145  4145 I bt_bluedroid: get_profile_interface sdp
,09-12 13:41:23.264  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:41:23.264  4145  4156 I bt_bluedroid: config_hci_snoop_log
,09-12 13:41:23.266  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
09-12 13:41:23.266   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 13:41:23.277  4145  4157 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 13:41:23.277  4145  4157 D BluetoothAdapterProperties: Setting state to 14
09-12 13:41:23.277  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 13:41:23.281  4145  4157 D BluetoothBondStateMachine: make
,09-12 13:41:23.284  4145  4163 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:41:23.293  4145  4145 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:41:23.293  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:41:23.295  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:23.296  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:41:23.296  4145  4145 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:41:23.296  4145  4145 D BtGatt.GattService: start()
09-12 13:41:23.296  4145  4145 I bt_bluedroid: get_profile_interface gatt
,09-12 13:41:23.297  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
09-12 13:41:23.297  4145  4145 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:41:23.305  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:41:23.305  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:41:23.305  4145  4145 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 13:41:23.305  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:23.306  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 13:41:23.306  4145  4157 I bt_bluedroid: enable
,09-12 13:41:23.307  4145  4158 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 13:41:23.307  4145  4158 I bt_hci  : start_up
,09-12 13:41:23.315  4145  4158 I bt_vendor: alloc value 0xb3a7c189
,09-12 13:41:23.315  4145  4158 I bt_vendor: init
,09-12 13:41:23.315  4145  4158 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 13:41:23.315  4145  4158 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:41:23.423  4145  4158 D bt_hci  : start_up starting async portion
,09-12 13:41:23.424  4145  4166 I bt_hci  : event_finish_startup
09-12 13:41:23.424  4145  4166 I bt_hci_h4: hal_open
09-12 13:41:23.424  4145  4166 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:41:23.432  4145  4166 I bt_userial_vendor: device fd = 51 open
,09-12 13:41:23.466  4145  4166 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:41:23.498  4145  4166 D bt_hwcfg: Chipset BCM4354A2
09-12 13:41:23.499  4145  4166 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 13:41:23.499  4145  4166 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:41:23.546   873  1317 D ConnectivityService: handlePromptUnvalidated 101
,09-12 13:41:24.171  4145  4166 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 13:41:24.172  4145  4166 D bt_hwcfg: Settlement delay -- 100 ms
09-12 13:41:24.173  4145  4166 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:41:24.289  4145  4166 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:41:24.291  4145  4166 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:41:24.319  4145  4166 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:41:24.319  4145  4166 I bt_vendor: firmware callback
09-12 13:41:24.320  4145  4166 I bt_hci  : firmware_config_callback
,09-12 13:41:24.331  4145  4168 I bt_btu  : btu_task pending for preload complete event
,09-12 13:41:24.331  4145  4168 I bt_btu_task: Bluetooth chip preload is complete
,09-12 13:41:24.331  4145  4168 I bt_btu  : btu_task received preload complete event
,09-12 13:41:24.341  4145  4168 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:41:24.341  4145  4168 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 13:41:24.342  4145  4168 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:41:24.342  4145  4168 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:41:24.342  4145  4168 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 13:41:24.343  4145  4168 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:41:24.343  4145  4168 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:41:24.343  4145  4168 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:41:24.343  4145  4168 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:41:24.344  4145  4168 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:41:24.344  4145  4168 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:41:24.344  4145  4168 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:41:24.344  4145  4168 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:41:24.345  4145  4168 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:41:24.345  4145  4168 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:41:24.477  4145  4168 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f9d9d
,09-12 13:41:24.477  4145  4168 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f9d9d 
,09-12 13:41:24.490  4145  4161 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:41:24.493  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:41:24.494  4145  4161 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:41:24.497  4145  4161 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:41:24.500  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:41:24.501  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:41:24.501  4145  4161 D bt_hci  : do_postload posting postload work item
,09-12 13:41:24.502  4145  4166 I bt_hci  : event_postload
09-12 13:41:24.502  4145  4166 I bt_vendor: sco_config_cb
09-12 13:41:24.502  4145  4166 I bt_hci  : sco_config_callback postload finished.
,09-12 13:41:24.507  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:24.511  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:24.514  4145  4161 D bt_bte_conf: Device ID record 1 : primary
09-12 13:41:24.515  4145  4161 D bt_bte_conf:   vendorId            = 000f
,09-12 13:41:24.515  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:24.515  4145  4161 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:41:24.516  4145  4161 D bt_bte_conf:   product             = 1200
09-12 13:41:24.516  4145  4161 D bt_bte_conf:   version             = 1436
,09-12 13:41:24.516  4145  4161 D bt_bte_conf:   clientExecutableURL = 
09-12 13:41:24.516  4145  4161 D bt_bte_conf:   serviceDescription  = 
09-12 13:41:24.516  4145  4161 D bt_bte_conf:   documentationURL    = 
09-12 13:41:24.517  4145  4161 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 13:41:24.517  4145  4166 I bt_vendor: low_power_mode_cb
09-12 13:41:24.517  4145  4158 D bt_stack_manager: event_start_up_stack finished
,09-12 13:41:24.518  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 13:41:24.518  4145  4157 D BluetoothAdapterProperties: Setting state to 15
09-12 13:41:24.518  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 13:41:24.519  4145  4157 I BluetoothAdapterState: Entering BleOnState
,09-12 13:41:24.527  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 13:41:24.527  4145  4157 D BluetoothAdapterProperties: Setting state to 11
09-12 13:41:24.527  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 13:41:24.532  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:24.532  4145  4145 D HeadsetService: Received start request. Starting profile...
09-12 13:41:24.536  4145  4145 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 13:41:24.537  4145  4145 D HeadsetStateMachine: make
09-12 13:41:24.539  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:24.541  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:24.543  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:24.547  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:41:24.547  4145  4145 D HeadsetStateMachine: max_hf_connections = 1
,09-12 13:41:24.547  4145  4145 I bt_bluedroid: get_profile_interface handsfree
09-12 13:41:24.548  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:41:24.548  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 13:41:24.551  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:24.552  4145  4145 D A2dpService: Received start request. Starting profile...
09-12 13:41:24.553  4145  4145 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 13:41:24.553  4145  4145 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:41:24.559  4145  4145 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:41:24.559  4145  4145 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:41:24.559  4145  4145 D A2dpStateMachine: make
,09-12 13:41:24.560  4145  4145 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:41:24.561  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:41:24.563  4145  4177 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:41:24.563  4145  4145 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:41:24.564  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:24.565  4145  4145 D HidService: Received start request. Starting profile...
,09-12 13:41:24.565  3920  3920 D BluetoothInputDevice: Proxy object connected
,09-12 13:41:24.565  4145  4145 I bt_bluedroid: get_profile_interface hidhost
09-12 13:41:24.565  4145  4161 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39db3e5
09-12 13:41:24.565  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 13:41:24.566  4145  4145 D HidService: setHidService(): set to: null
09-12 13:41:24.566  4145  4145 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 13:41:24.566  3920  3920 D HidProfile: Bluetooth service connected
09-12 13:41:24.567  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:24.567  4145  4145 D HealthService: Received start request. Starting profile...
09-12 13:41:24.568  4145  4145 I bt_bluedroid: get_profile_interface health
,09-12 13:41:24.569  4145  4145 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:41:24.570  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:24.571  3920  3920 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:41:24.572  4145  4145 D PanService: Received start request. Starting profile...
09-12 13:41:24.572  3920  3920 D PanProfile: Bluetooth service connected
09-12 13:41:24.572  4145  4145 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:41:24.572  4145  4145 I bt_bluedroid: get_profile_interface pan
,09-12 13:41:24.572  4145  4161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:41:24.576  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:24.579  4145  4145 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
09-12 13:41:24.580  3920  3920 D BluetoothMap: Proxy object connected
09-12 13:41:24.581  4145  4145 D BluetoothMapService: Received start request. Starting profile...
09-12 13:41:24.581  4145  4145 D BluetoothMapService: start()
09-12 13:41:24.581  3920  3920 D MapProfile: Bluetooth service connected
09-12 13:41:24.581  3920  3920 D BluetoothMap: getConnectedDevices()
09-12 13:41:24.582  3920  3920 D BluetoothMap: Bluetooth is Not enabled
,09-12 13:41:24.583  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 13:41:24.584  4145  4145 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 13:41:24.584  4145  4145 D BluetoothMapAppObserver: createReceiver()
,09-12 13:41:24.585  4145  4145 D BluetoothMapAppObserver: initObservers()
09-12 13:41:24.585  4145  4145 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:41:24.592  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:24.592  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:41:24.592  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:24.592  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:24.594  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:24.594  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:24.595  4145  4175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:24.595  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:41:24.596  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:24.596  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:24.596  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:24.596  4145  4145 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:24.596  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:41:24.596  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:24.598  4145  4145 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:24.599  4145  4145 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:41:24.599  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:24.599  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:24.599  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:41:24.599  4145  4157 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:41:24.599  4145  4157 D BluetoothAdapterProperties: State =  11
09-12 13:41:24.600  4145  4157 D BluetoothAdapterProperties: Setting state to 12
,09-12 13:41:24.600  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 13:41:24.601  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:41:24.602  4145  4161 D BluetoothAdapterProperties: Scan Mode:21
,09-12 13:41:24.602  4145  4161 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:41:24.602  4145  4157 I BluetoothAdapterState: Entering OnState
09-12 13:41:24.604   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:41:24.605  1360  1384 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:41:24.606   873   873 D BluetoothA2dp: Proxy object connected
09-12 13:41:24.606  1360  1360 D BluetoothA2dp: Proxy object connected
,09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:24.606  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:24.608  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:24.608  1360  2049 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:24.609  1360  1360 D BluetoothMap: Proxy object connected
09-12 13:41:24.609  1360  1360 D MapProfile: Bluetooth service connected
09-12 13:41:24.609  1360  1360 D BluetoothMap: getConnectedDevices()
09-12 13:41:24.609   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:24.609  1949  2141 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:24.610  3920  3932 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:41:24.612  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:24.613  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:24.613  3920  3933 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:41:24.613   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:24.614  4145  4145 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 13:41:24.614  1360  1372 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:41:24.615  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:41:24.616  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:24.618  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:41:24.618  1360  1360 D PanProfile: Bluetooth service connected
09-12 13:41:24.618  4145  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:41:24.618   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:24.618  3920  3932 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:41:24.619  1360  2049 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:41:24.619  4145  4145 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:41:24.619  4145  4145 D ObexServerSockets0: startAccept()
,09-12 13:41:24.620  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:24.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:41:24.621  1360  1360 D BluetoothInputDevice: Proxy object connected
09-12 13:41:24.621  1360  1360 D HidProfile: Bluetooth service connected
,09-12 13:41:24.622  1360  1372 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:41:24.622  4145  4145 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 13:41:24.622  4145  4145 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 13:41:24.623  4145  4186 D ObexServerSockets0: Accepting socket connection...
,09-12 13:41:24.624  3920  3933 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:41:24.624  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:24.624  4145  4185 D ObexServerSockets0: Accepting socket connection...
,09-12 13:41:24.626   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:41:24.627  4145  4145 D BluetoothMapService: onReceive
09-12 13:41:24.627  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:41:24.627  4145  4145 D BluetoothMapService: STATE_ON
,09-12 13:41:24.629  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:24.629  3920  3920 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 13:41:24.630  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:24.633  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:24.634  3920  3920 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 13:41:24.639  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:41:24.641  3920  3920 D BluetoothA2dp: Proxy object connected
,09-12 13:41:24.644  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:24.648  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:41:24.654  3920  3920 D BluetoothPbap: Proxy object connected
09-12 13:41:24.654  1360  1360 D BluetoothPbap: Proxy object connected
,09-12 13:41:24.654  1360  1360 D PbapServerProfile: Bluetooth service connected
09-12 13:41:24.654  4145  4145 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:41:24.654  3920  3920 D PbapServerProfile: Bluetooth service connected
09-12 13:41:24.654  4145  4145 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:41:24.662  4145  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:41:24.679  4145  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:41:24.680  4145  4194 I BtOppRfcommListener: Accept thread started.
,09-12 13:41:24.711  1360  1384 D BluetoothHeadset: Proxy object connected
,09-12 13:41:24.711   873   873 D BluetoothHeadset: Proxy object connected
09-12 13:41:24.711  1360  1360 D HeadsetProfile: Bluetooth service connected
,09-12 13:41:24.711   873   873 D BluetoothHeadset: Proxy object connected
,09-12 13:41:24.711  1949  2269 D BluetoothHeadset: Proxy object connected
09-12 13:41:24.712   873   873 D BluetoothHeadset: Proxy object connected
,09-12 13:41:24.713   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:41:24.718   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:41:24.737  3920  3932 D BluetoothHeadset: Proxy object connected
,09-12 13:41:24.739  3920  3920 D HeadsetProfile: Bluetooth service connected
,09-12 13:41:28.069  4145  4157 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 13:41:28.070  4145  4157 D BluetoothAdapterProperties: Setting state to 13
,09-12 13:41:28.070  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,09-12 13:41:28.072  4145  4157 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 13:41:28.081  4145  4145 D BluetoothMapService: onReceive
,09-12 13:41:28.081  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:41:28.082  4145  4145 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:41:28.082  4145  4145 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:41:28.083  4145  4145 D BluetoothMapService: MAP Service closeService in
09-12 13:41:28.083  4145  4145 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 13:41:28.083  4145  4145 D ObexServerSockets0: shutdown(block = true)
09-12 13:41:28.084  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:28.085  4145  4185 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:28.085  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:28.086  4145  4145 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:41:28.087  4145  4186 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 13:41:28.088  4145  4172 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-12 13:41:28.088  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:28.089  4145  4145 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:41:28.089  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:28.089  4145  4145 I BtOppRfcommListener: stopping Accept Thread
09-12 13:41:28.092  4145  4194 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:41:28.093  4145  4194 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 13:41:28.096  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:41:28.097  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 13:41:28.100  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:28.100  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:28.102  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:41:28.102  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:28.102  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:28.107  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:28.107  4145  4145 D HeadsetService: Received stop request...Stopping profile...
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:28.107  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:41:28.109  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:41:28.109  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:28.109  1360  1384 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:28.110  3920  3932 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:28.111   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:28.111   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:28.111  4145  4145 D A2dpService: Received stop request...Stopping profile...
,09-12 13:41:28.111  1949  1962 D BluetoothHeadset: Proxy object disconnected
09-12 13:41:28.112   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 13:41:28.112  1360  1360 D HeadsetProfile: Bluetooth service disconnected
09-12 13:41:28.112  4145  4177 D A2dpStateMachine: Exit Disconnected: -1
09-12 13:41:28.112  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:28.114  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:28.114   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 13:41:28.115  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:28.117  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:28.118  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:28.118  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:28.118  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:28.120  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:41:28.120  4145  4145 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 13:41:28.120  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:41:28.121  4145  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:28.121  4145  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:28.121  4145  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:28.121  4145  4161 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 13:41:28.122  4145  4145 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:41:28.122  4145  4145 D HidService: Received stop request...Stopping profile...
,09-12 13:41:28.122  4145  4145 D HidService: Stopping Bluetooth HidService
09-12 13:41:28.126  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:28.126  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:41:28.127  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:28.127  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:28.128  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 13:41:28.128  4145  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:28.128  4145  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:41:28.129  4145  4168 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:41:28.129  4145  4168 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:41:28.129  4145  4168 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:41:28.129  4145  4168 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:41:28.130  4145  4145 D HealthService: Received stop request...Stopping profile...
09-12 13:41:28.132  1360  1360 D BluetoothA2dp: Proxy object disconnected
09-12 13:41:28.132  1360  1360 D BluetoothInputDevice: Proxy object disconnected
09-12 13:41:28.132  1360  1360 D HidProfile: Bluetooth service disconnected
,09-12 13:41:28.134  1360  1360 D BluetoothPbap: Proxy object disconnected
,09-12 13:41:28.134  1360  1360 D PbapServerProfile: Bluetooth service disconnected
09-12 13:41:28.134  4145  4145 D PanService: Received stop request...Stopping profile...
,09-12 13:41:28.136  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:41:28.136  1360  1360 D PanProfile: Bluetooth service disconnected
09-12 13:41:28.136  4145  4145 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:41:28.136  4145  4145 D BluetoothMapService: stop()
,09-12 13:41:28.137  4145  4145 D BluetoothMapAppObserver: deinitObservers()
09-12 13:41:28.137  4145  4145 D BluetoothMapAppObserver: removeReceiver()
09-12 13:41:28.138  1360  1360 D BluetoothMap: Proxy object disconnected
,09-12 13:41:28.138  1360  1360 D MapProfile: Bluetooth service disconnected
,09-12 13:41:28.139  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:28.139  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:41:28.139  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:28.139  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:28.140  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:41:28.141  4145  4145 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:41:28.141  4145  4145 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 13:41:28.142  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:28.142  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:28.142  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:41:28.143  4145  4161 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 13:41:28.143  3920  3920 D HeadsetProfile: Bluetooth service disconnected
,09-12 13:41:28.144  3920  3920 D BluetoothA2dp: Proxy object disconnected
,09-12 13:41:28.144  3920  3920 D BluetoothInputDevice: Proxy object disconnected
,09-12 13:41:28.144  3920  3920 D HidProfile: Bluetooth service disconnected
09-12 13:41:28.142  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:28.144  3920  3920 D BluetoothPbap: Proxy object disconnected
09-12 13:41:28.144  3920  3920 D PbapServerProfile: Bluetooth service disconnected
,09-12 13:41:28.144  4145  4145 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-12 13:41:28.145  4145  4161 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 13:41:28.145  3920  3920 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:41:28.145  4145  4145 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 13:41:28.146  3920  3920 D PanProfile: Bluetooth service disconnected
09-12 13:41:28.146  4145  4145 V BluetoothAdapterState: isTurningOff()=true
09-12 13:41:28.146  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:41:28.146  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:28.146  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:28.147  4145  4145 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:41:28.147  4145  4145 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:41:28.148  4145  4145 D BluetoothMapService: MAP Service closeService in
,09-12 13:41:28.148  4145  4145 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:41:28.148  4145  4145 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:28.148  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:28.148  4145  4145 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:28.149  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-12 13:41:28.149  4145  4157 D BluetoothAdapterProperties: Setting state to 15
09-12 13:41:28.149  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:41:28.149  3920  3920 D BluetoothMap: Proxy object disconnected
,09-12 13:41:28.149  3920  3920 D MapProfile: Bluetooth service disconnected
09-12 13:41:28.149  1360  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:41:28.150   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:41:28.150  1360  1384 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:41:28.150  4145  4157 I BluetoothAdapterState: Entering BleOnState
09-12 13:41:28.152  3920  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:41:28.152  4145  4145 D BluetoothMapService: cleanup()
09-12 13:41:28.152  4145  4145 D BluetoothMapService: MAP Service closeService in
,09-12 13:41:28.152  1360  2049 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:41:28.152  3920  3932 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:41:28.153   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:28.153  1949  2141 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:41:28.154  3920  3933 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:41:28.154  3920  3932 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:41:28.154   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:28.155  1360  1372 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:41:28.155   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:41:28.155  3920  3933 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:41:28.156  1360  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:41:28.157  1360  2049 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:41:28.158  3920  3932 D BluetoothPan: onBluetoothStateChange on: false
,09-12 13:41:28.158  4145  4157 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 13:41:28.159  4145  4157 D BluetoothAdapterProperties: Setting state to 16
09-12 13:41:28.159  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 13:41:28.160  4145  4157 D BluetoothAdapterProperties: onBleDisable
09-12 13:41:28.161  4145  4157 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:41:28.161  4145  4158 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:41:28.162  4145  4168 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:41:28.162  4145  4168 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:41:28.163  4145  4161 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:41:28.163  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:28.164  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:28.165  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:41:28.166  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:28.168  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:28.169  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:28.170  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:28.170  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:28.178  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:41:28.368  4145  4161 I bt_hci  : shut_down
,09-12 13:41:28.392  4145  4166 D bt_hwcfg: hw_epilog_process
,09-12 13:41:28.392  4145  4166 I bt_vendor: low_power_mode_cb
,09-12 13:41:28.412  4145  4166 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:41:28.413  4145  4166 I bt_vendor: epilog_cb
,09-12 13:41:28.413  4145  4166 I bt_hci  : epilog_finished_callback
,09-12 13:41:28.419  4145  4161 I bt_hci_h4: hal_close
,09-12 13:41:28.421  4145  4161 I bt_userial_vendor: device fd = 51 close
,09-12 13:41:28.546  4145  4158 D bt_stack_manager: event_shut_down_stack finished.
,09-12 13:41:28.547  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 13:41:28.555  4145  4145 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:41:28.555  4145  4157 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 13:41:28.556  4145  4145 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 13:41:28.556  4145  4145 D BtGatt.GattService: stop()
,09-12 13:41:28.557  4145  4145 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:41:28.563  4145  4145 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:41:28.563  4145  4145 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:41:28.564  4145  4145 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:28.564  4145  4145 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 13:41:28.565  4145  4157 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 13:41:28.566  4145  4157 D BluetoothAdapterProperties: Setting state to 10
09-12 13:41:28.566  4145  4157 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 13:41:28.567  4145  4157 I BluetoothAdapterState: Entering OffState
09-12 13:41:28.570   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 13:41:28.584  4145  4145 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 13:41:28.584  4145  4145 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:41:28.585  4145  4145 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 13:41:28.586  4145  4158 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:41:28.589  4145  4158 D bt_stack_manager: event_clean_up_stack finished.
,09-12 13:41:28.592  4145  4145 I art     : System.exit called, status: 0
,09-12 13:41:28.592  4145  4145 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:41:28.632   873  2233 I ActivityManager: Process com.android.bluetooth (pid 4145) has died
,09-12 13:41:32.819  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:32.845  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:32.848  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:32.913  1507  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 13:41:32.913  1507  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-12 13:41:32.914  1507  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:32.914  1507  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:32.940  3549  3549 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 13:41:32.940  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 13:41:32.941  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-12 13:41:33.066  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:33.067  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:33.071  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:33.072  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f70b4ce removed from the list
,09-12 13:41:33.072  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:33.072  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:33.073  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:33.076  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:41:33.076  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c362afc added. We now have 4 listener(s)
,09-12 13:41:33.077  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:41:33.078  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:33.079  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c362afc removed from the list
,09-12 13:41:33.079  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:33.079  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:33.080  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:33.082  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:41:33.083  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f114585 added. We now have 4 listener(s)
,09-12 13:41:33.083  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:41:38.093  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:38.114   873   890 I ActivityManager: Start proc 4205:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:41:38.213  4205  4205 D AdapterServiceConfig: Adding HeadsetService
09-12 13:41:38.213  4205  4205 D AdapterServiceConfig: Adding A2dpService
09-12 13:41:38.213  4205  4205 D AdapterServiceConfig: Adding HidService
09-12 13:41:38.213  4205  4205 D AdapterServiceConfig: Adding HealthService
09-12 13:41:38.213  4205  4205 D AdapterServiceConfig: Adding PanService
09-12 13:41:38.214  4205  4205 D AdapterServiceConfig: Adding GattService
09-12 13:41:38.214  4205  4205 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:41:38.226  4205  4205 D BluetoothAdapterState: make() - Creating AdapterState
09-12 13:41:38.225   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e909f7b:true
,09-12 13:41:38.229  4205  4205 I bt_bluedroid: init
09-12 13:41:38.229  4205  4217 I BluetoothAdapterState: Entering OffState
,09-12 13:41:38.235  4205  4218 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 13:41:38.235  4205  4218 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 13:41:38.258  4205  4218 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 13:41:38.258  4205  4218 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 13:41:38.259  4205  4205 I bt_bluedroid: get_profile_interface socket
,09-12 13:41:38.262  4205  4205 I bt_bluedroid: get_profile_interface sdp
,09-12 13:41:38.264  4205  4221 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:41:38.269  4205  4221 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:41:38.269  4205  4216 I bt_bluedroid: config_hci_snoop_log
,09-12 13:41:38.271   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 13:41:38.279  4205  4217 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 13:41:38.280  4205  4217 D BluetoothAdapterProperties: Setting state to 14
,09-12 13:41:38.280  4205  4217 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 13:41:38.284  4205  4217 D BluetoothBondStateMachine: make
,09-12 13:41:38.288  4205  4222 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:41:38.293  4205  4217 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:41:38.295  4205  4205 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:41:38.300  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:38.301  4205  4205 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:41:38.302  4205  4205 D BtGatt.GattService: Received start request. Starting profile...
,09-12 13:41:38.302  4205  4205 D BtGatt.GattService: start()
09-12 13:41:38.302  4205  4205 I bt_bluedroid: get_profile_interface gatt
,09-12 13:41:38.303  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:38.304  4205  4205 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:41:38.313  4205  4205 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:41:38.313  4205  4205 V BluetoothAdapterState: isTurningOn()=false
09-12 13:41:38.313  4205  4205 V BluetoothAdapterState: isBleTurningOn()=true
09-12 13:41:38.313  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:38.313  4205  4217 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:41:38.314  4205  4217 I bt_bluedroid: enable
,09-12 13:41:38.314  4205  4218 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 13:41:38.315  4205  4218 I bt_hci  : start_up
,09-12 13:41:38.322  4205  4218 I bt_vendor: alloc value 0xb3a7c189
,09-12 13:41:38.322  4205  4218 I bt_vendor: init
09-12 13:41:38.322  4205  4218 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 13:41:38.322  4205  4218 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:41:38.431  4205  4218 D bt_hci  : start_up starting async portion
,09-12 13:41:38.432  4205  4225 I bt_hci  : event_finish_startup
09-12 13:41:38.432  4205  4225 I bt_hci_h4: hal_open
09-12 13:41:38.432  4205  4225 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:41:38.442  4205  4225 I bt_userial_vendor: device fd = 51 open
,09-12 13:41:38.473  4205  4225 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:41:38.505  4205  4225 D bt_hwcfg: Chipset BCM4354A2
09-12 13:41:38.505  4205  4225 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 13:41:38.506  4205  4225 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:41:39.164  4205  4225 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 13:41:39.165  4205  4225 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 13:41:39.167  4205  4225 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:41:39.283  4205  4225 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:41:39.285  4205  4225 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:41:39.313  4205  4225 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:41:39.313  4205  4225 I bt_vendor: firmware callback
09-12 13:41:39.314  4205  4225 I bt_hci  : firmware_config_callback
,09-12 13:41:39.326  4205  4227 I bt_btu  : btu_task pending for preload complete event
,09-12 13:41:39.327  4205  4227 I bt_btu_task: Bluetooth chip preload is complete
09-12 13:41:39.327  4205  4227 I bt_btu  : btu_task received preload complete event
,09-12 13:41:39.337  4205  4227 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:41:39.337  4205  4227 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:41:39.337  4205  4227 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:41:39.338  4205  4227 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:41:39.338  4205  4227 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:41:39.338  4205  4227 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:41:39.338  4205  4227 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 13:41:39.339  4205  4227 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:41:39.339  4205  4227 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 13:41:39.339  4205  4227 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:41:39.339  4205  4227 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:41:39.339  4205  4227 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 13:41:39.340  4205  4227 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:41:39.340  4205  4227 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-12 13:41:39.340  4205  4227 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:41:39.467  4205  4227 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f9d9d
,09-12 13:41:39.467  4205  4227 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f9d9d 
,09-12 13:41:39.492  4205  4221 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:41:39.494  4205  4221 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:41:39.495  4205  4221 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:41:39.500  4205  4221 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:41:39.503  4205  4221 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:41:39.503  4205  4221 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:41:39.504  4205  4221 D bt_hci  : do_postload posting postload work item
,09-12 13:41:39.504  4205  4225 I bt_hci  : event_postload
,09-12 13:41:39.504  4205  4225 I bt_vendor: sco_config_cb
09-12 13:41:39.505  4205  4225 I bt_hci  : sco_config_callback postload finished.
,09-12 13:41:39.508  4205  4221 D bt_bte_conf: Device ID record 1 : primary
09-12 13:41:39.508  4205  4221 D bt_bte_conf:   vendorId            = 000f
,09-12 13:41:39.509  4205  4221 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:41:39.509  4205  4221 D bt_bte_conf:   product             = 1200
,09-12 13:41:39.509  4205  4221 D bt_bte_conf:   version             = 1436
,09-12 13:41:39.509  4205  4221 D bt_bte_conf:   clientExecutableURL = 
09-12 13:41:39.510  4205  4221 D bt_bte_conf:   serviceDescription  = 
,09-12 13:41:39.510  4205  4221 D bt_bte_conf:   documentationURL    = 
09-12 13:41:39.510  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:39.510  4205  4221 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 13:41:39.510  4205  4218 D bt_stack_manager: event_start_up_stack finished
,09-12 13:41:39.512  4205  4217 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 13:41:39.513  4205  4225 I bt_vendor: low_power_mode_cb
,09-12 13:41:39.513  4205  4217 D BluetoothAdapterProperties: Setting state to 15
09-12 13:41:39.513  4205  4217 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 13:41:39.514  4205  4217 I BluetoothAdapterState: Entering BleOnState
09-12 13:41:39.516  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:39.519  4205  4217 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 13:41:39.519  4205  4217 D BluetoothAdapterProperties: Setting state to 11
,09-12 13:41:39.520  4205  4217 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 13:41:39.529  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:39.533  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:39.537  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
09-12 13:41:39.538  4205  4205 D HeadsetService: Received start request. Starting profile...
,09-12 13:41:39.542  4205  4205 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 13:41:39.543  4205  4205 D HeadsetStateMachine: make
,09-12 13:41:39.550  4205  4217 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:41:39.552  4205  4205 D HeadsetStateMachine: max_hf_connections = 1
,09-12 13:41:39.553  4205  4205 I bt_bluedroid: get_profile_interface handsfree
,09-12 13:41:39.553  4205  4221 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-12 13:41:39.553  4205  4221 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-12 13:41:39.560  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:39.561  4205  4205 D A2dpService: Received start request. Starting profile...
,09-12 13:41:39.561  4205  4205 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:41:39.562  4205  4205 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:41:39.569  4205  4205 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:41:39.569  4205  4205 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 13:41:39.569  4205  4205 D A2dpStateMachine: make
09-12 13:41:39.570  4205  4205 I bt_bluedroid: get_profile_interface a2dp,
,09-12 13:41:39.572  4205  4221 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:41:39.576  4205  4236 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:41:39.579  4205  4205 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:41:39.580  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:39.581  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:39.583  4205  4205 D HidService: Received start request. Starting profile...
09-12 13:41:39.583  4205  4205 I bt_bluedroid: get_profile_interface hidhost,
,09-12 13:41:39.584  4205  4221 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39db3e5
09-12 13:41:39.584  4205  4221 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 13:41:39.584  4205  4205 D HidService: setHidService(): set to: null
09-12 13:41:39.586  4205  4205 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:41:39.587  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:39.588  4205  4205 D HealthService: Received start request. Starting profile...
,09-12 13:41:39.591  4205  4205 I bt_bluedroid: get_profile_interface health
,09-12 13:41:39.593  4205  4205 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:41:39.593  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:41:39.594  4205  4205 D PanService: Received start request. Starting profile...
,09-12 13:41:39.594  4205  4205 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:41:39.594  4205  4205 I bt_bluedroid: get_profile_interface pan
09-12 13:41:39.595  4205  4221 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:41:39.598  4205  4205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
09-12 13:41:39.598  4205  4205 D BluetoothMapService: Received start request. Starting profile...
09-12 13:41:39.598  4205  4205 D BluetoothMapService: start()
,09-12 13:41:39.600  4205  4205 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 13:41:39.601  4205  4205 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 13:41:39.601  4205  4205 D BluetoothMapAppObserver: createReceiver()
09-12 13:41:39.602  4205  4205 D BluetoothMapAppObserver: initObservers()
09-12 13:41:39.602  4205  4205 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:41:39.608  4205  4205 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:39.608  4205  4205 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:39.608  4205  4205 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:39.608  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:39.610  4205  4205 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:39.610  4205  4205 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:39.610  4205  4205 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:39.610  4205  4234 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:41:39.610  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:41:39.612  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isTurningOff()=false
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isTurningOn()=true
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:41:39.613  4205  4205 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:41:39.613  4205  4217 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:41:39.613  4205  4217 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:41:39.613  4205  4217 D BluetoothAdapterProperties: State =  11
,09-12 13:41:39.617  4205  4221 D BluetoothAdapterProperties: Scan Mode:21
,09-12 13:41:39.617  4205  4217 D BluetoothAdapterProperties: Setting state to 12
,09-12 13:41:39.617  4205  4217 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:41:39.617  4205  4221 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:41:39.617  1360  2049 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:41:39.617  4205  4217 I BluetoothAdapterState: Entering OnState
09-12 13:41:39.619   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:41:39.619  1360  1372 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:41:39.620   873   873 D BluetoothA2dp: Proxy object connected
09-12 13:41:39.620  1360  1360 D BluetoothA2dp: Proxy object connected
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:39.621  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:39.622  3920  3933 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:39.622  1360  1360 D BluetoothMap: Proxy object connected
09-12 13:41:39.623  1360  1360 D MapProfile: Bluetooth service connected
09-12 13:41:39.623  1360  1360 D BluetoothMap: getConnectedDevices()
09-12 13:41:39.623  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:39.623  1360  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:41:39.624  3920  3932 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:39.626  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:39.627  4205  4205 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:41:39.627   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:39.627  4205  4205 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 13:41:39.627  3920  3920 D BluetoothA2dp: Proxy object connected
09-12 13:41:39.628  1949  1966 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:39.628  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:39.628  3920  3933 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:41:39.629  4205  4205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:41:39.630  4205  4205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:41:39.631  3920  4202 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:41:39.631  4205  4205 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:41:39.631  4205  4205 D ObexServerSockets0: startAccept()
09-12 13:41:39.631  4205  4205 D ObexServerSockets0: prepareForNewConnect()
09-12 13:41:39.633   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:41:39.633  1360  1372 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:41:39.633  4205  4205 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 13:41:39.634  4205  4205 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 13:41:39.634   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:41:39.635  4205  4242 D ObexServerSockets0: Accepting socket connection...
,09-12 13:41:39.635  3920  3933 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:41:39.635  4205  4243 D ObexServerSockets0: Accepting socket connection...
09-12 13:41:39.636  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:41:39.636  1360  1360 D PanProfile: Bluetooth service connected
09-12 13:41:39.636  1360  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:41:39.638  1360  1360 D BluetoothInputDevice: Proxy object connected
09-12 13:41:39.638  1360  1360 D HidProfile: Bluetooth service connected
09-12 13:41:39.638  1360  2049 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:41:39.639  3920  3920 D BluetoothMap: Proxy object connected
09-12 13:41:39.639  3920  4202 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:41:39.642   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:41:39.645  4205  4205 D BluetoothMapService: onReceive
,09-12 13:41:39.645  4205  4205 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:41:39.645  4205  4205 D BluetoothMapService: STATE_ON
09-12 13:41:39.645  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:39.646  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:41:39.639  3920  3920 D MapProfile: Bluetooth service connected
,09-12 13:41:39.646  3920  3920 D BluetoothMap: getConnectedDevices()
,09-12 13:41:39.648  3920  3920 D BluetoothInputDevice: Proxy object connected
09-12 13:41:39.648  3920  3920 D HidProfile: Bluetooth service connected
09-12 13:41:39.649  3920  3920 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:41:39.650  3920  3920 D PanProfile: Bluetooth service connected
,09-12 13:41:39.654  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:41:39.660  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:41:39.664  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:41:39.671  1360  1360 D BluetoothPbap: Proxy object connected
,09-12 13:41:39.671  1360  1360 D PbapServerProfile: Bluetooth service connected
09-12 13:41:39.671  3920  3920 D BluetoothPbap: Proxy object connected
09-12 13:41:39.671  3920  3920 D PbapServerProfile: Bluetooth service connected
,09-12 13:41:39.676  4205  4205 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:41:39.676  4205  4205 D ObexServerSockets0: prepareForNewConnect()
,09-12 13:41:39.680  4205  4248 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:41:39.693  4205  4252 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:41:39.694  4205  4252 I BtOppRfcommListener: Accept thread started.
,09-12 13:41:39.724  1360  1372 D BluetoothHeadset: Proxy object connected
,09-12 13:41:39.724  1360  1360 D HeadsetProfile: Bluetooth service connected
,09-12 13:41:39.725  3920  3933 D BluetoothHeadset: Proxy object connected
09-12 13:41:39.725   873   873 D BluetoothHeadset: Proxy object connected
,09-12 13:41:39.725   873   873 D BluetoothHeadset: Proxy object connected
09-12 13:41:39.726  1949  1962 D BluetoothHeadset: Proxy object connected
,09-12 13:41:39.726   873   873 D BluetoothHeadset: Proxy object connected
09-12 13:41:39.727   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:41:39.725  3920  3920 D HeadsetProfile: Bluetooth service connected
09-12 13:41:39.728  1949  2141 D BluetoothHeadset: Proxy object connected
,09-12 13:41:39.733   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:41:39.735   873   890 D BluetoothHeadset: Proxy object connected
,09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:43.110  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:41:43.117  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:43.118  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:41:43.118  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f114585 removed from the list
09-12 13:41:43.120  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:41:43.121  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:41:43.122  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:43.128  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:41:43.128  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7674fda added. We now have 4 listener(s)
,09-12 13:41:43.129  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:41:43.134   873  1990 D WifiService: setWifiEnabled: false pid=3837, uid=10000
09-12 13:41:43.134   873  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:41:48.147  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:41:48.148   873  2233 D WifiService: setWifiEnabled: true pid=3837, uid=10000
09-12 13:41:48.149   873  2233 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:41:48.161   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:48.178  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:41:48.184   873  1315 D WifiConfigStore: loaded 0 passpoint configs
09-12 13:41:48.186   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 13:41:48.186  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:41:48.187   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 13:41:48.187   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 13:41:48.188   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:41:48.188   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 13:41:48.188   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:41:48.201  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:41:48.201   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 13:41:48.202   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:41:48.203   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:48.206  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:41:48.254   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 13:41:48.254   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:41:48.256   873  1315 E native  : do suspend true
,09-12 13:41:48.281   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:41:48.283   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-12 13:41:48.288   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:41:49.496   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-12 13:41:49.642   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.00 rxSuccessRate=9.19 delta 1000 -> 994
,09-12 13:41:49.643   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 13:41:49.643   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:49.663   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:41:49.726   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:41:49.732  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:41:50.170  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:41:50.223  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:41:50.224  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:41:50.235   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:41:50.253   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:41:50.254   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:50.255   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:41:50.282   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:41:50.299   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:50.301   873  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 13:41:50.309   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:41:50.327   873  4262 D DhcpClient: Receive thread started
,09-12 13:41:50.426   873  1315 E native  : do suspend false
,09-12 13:41:50.454   873  2061 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:41:50.470   873  4262 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-12 13:41:50.471   873  2061 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-12 13:41:50.475   873  2061 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:41:50.490   873  4262 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:41:50.491   873  2061 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:41:50.499   373   871 D CommandListener: Setting iface cfg
,09-12 13:41:50.511   873  2061 D DhcpClient: Scheduling renewal in 86399s
09-12 13:41:50.511   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:41:50.513   873  1315 E native  : do suspend true
,09-12 13:41:50.540   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:41:50.543   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:41:50.544   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 13:41:50.547   873  1317 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 13:41:50.555   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:41:50.604   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 13:41:50.604   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 13:41:50.608   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 13:41:50.609   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 13:41:50.611   873  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 13:41:50.627   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 13:41:50.632   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 13:41:50.633   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 13:41:50.633   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 13:41:50.633   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:41:50.634   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 13:41:50.634   873  1317 D ConnectivityService:    accepting network in place of null
09-12 13:41:50.635   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:41:50.658   873  4261 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211838, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:41:50.667   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:50.698   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:41:50.703   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 13:41:50.704   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:41:50.713   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 13:41:50.714   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:50.727  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:41:50.731  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:50.739  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:41:50.742  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:41:50.745  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 13:41:50.748   873  4260 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:41:50.753  1736  1736 D SystemUpdateService: onCreate
,09-12 13:41:50.766  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:41:50.786  1736  4271 I SystemUpdateService: active receiver: enabled
,09-12 13:41:50.804  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:50.813   873  4260 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:41:51 GMT], X-Android-Received-Millis=[1473680510812], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473680510789]}
,09-12 13:41:50.816   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:41:50.817   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 13:41:50.817   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 13:41:50.824   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:41:50.829  1736  4271 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:41:50.851  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-12 13:41:50.852  1736  2615 I iu.UploadsManager: num queued entries: 0
09-12 13:41:50.852  1736  2615 I iu.UploadsManager: num updated entries: 0
09-12 13:41:50.853  1736  2615 I iu.SyncManager: NEXT; no task
,09-12 13:41:50.846  1736  4271 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 13:41:50.867  1736  4271 I SystemUpdateService: now status is 0 (complete)
,09-12 13:41:50.867  1736  4271 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:41:50.868  1736  4271 I SystemUpdateService: file has been verified
,09-12 13:41:50.869  1736  4271 I SystemUpdateService: OTA package size = 12249756
,09-12 13:41:50.871  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:41:50.873  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:41:50.875  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:41:50.891  3975  3975 D SprintDMHelper: simOperator: 
,09-12 13:41:50.891  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:41:50.903  1736  4276 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 13:41:50.903  1736  4276 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 13:41:50.905  1736  4276 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 13:41:50.924  1736  4271 I SystemUpdateService: showing system update notification
,09-12 13:41:50.958  3804  4281 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 13:41:51.033  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:51.038  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:41:51.041  3094  4278 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:41:51.066  1507  4282 I VacuumService: Vacuum at: now=1473680511066 tag=VacuumService
,09-12 13:41:51.169  1736  1736 D SystemUpdateService: onDestroy
,09-12 13:41:51.191  3804  4289 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 13:41:51.246  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 13:41:51.246  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 13:41:51.246  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:41:51.246  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:51.337  1507  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 13:41:51.337  1507  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 13:41:51.337  1507  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:51.338  1507  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:51.340  1507  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 13:41:51.340  1507  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 13:41:51.340  1507  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:41:51.342  1507  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:51.360  3804  4289 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 13:41:51.360  3804  4281 E BooksSync: Soft error
09-12 13:41:51.360  3804  4281 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:41:51.360  3804  4281 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 13:41:51.361  3804  4281 E BooksSync: Sync error
09-12 13:41:51.361  3804  4281 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:41:51.361  3804  4281 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 13:41:51.361  3804  4281 I BooksSync: Finished books sync
09-12 13:41:51.364   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 186584, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:41:51.425  3763  4280 V KeepSync: Connecting to GoogleApiClient
,09-12 13:41:51.425   873  1956 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 13:41:51.430  1736  4276 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-12 13:41:51.435  1507  4285 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-12 13:41:51.442  1507  4285 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 13:41:51.504  1507  4285 W Uploader:  no longer exists, so no auth token.
,09-12 13:41:51.561  1507  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 13:41:51.561  1507  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 13:41:51.561  1507  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:41:51.561  1507  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:51.575  1736  4293 V BaseAuthAsyncOperation: access token request failed
,09-12 13:41:51.576  3763  4280 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 13:41:51.625  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-12 13:41:51.625  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 13:41:51.625  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:51.626  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:51.646  3763  4280 E KeepSync: IOException
09-12 13:41:51.646  3763  4280 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 13:41:51.646  3763  4280 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:41:51.646  3763  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 13:41:51.646  3763  4280 E KeepSync: 	... 10 more
,09-12 13:41:51.647  3763  4280 W KeepSync: Sync result 2
,09-12 13:41:51.659   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 184231, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:41:51.704   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 13:41:51.763  1887  1925 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-12 13:41:51.763  1887  1925 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-12 13:41:51.775  1507  1507 I ConfigService: onCreate
,09-12 13:41:52.662  1507  4285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 13:41:52.662  1507  4285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 13:41:52.662  1507  4285 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:52.662  1507  4285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:52.678  1507  4285 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:41:52.678  1507  4285 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 13:41:52.678  1507  4285 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 13:41:53.107  1507  4285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-12 13:41:53.107  1507  4285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-12 13:41:53.107  1507  4285 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:53.107  1507  4285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:53.126  1507  4285 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:41:53.126  1507  4285 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 13:41:53.126  1507  4285 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:41:53.167  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:41:53.169  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:41:53.170  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:41:53.170  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7674fda removed from the list
09-12 13:41:53.170  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:41:53.170  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:41:53.170  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:41:53.176  3837  4301 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-12 13:41:53.176  3837  4301 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:41:53.586  1507  4285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-12 13:41:53.586  1507  4285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-12 13:41:53.586  1507  4285 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:41:53.586  1507  4285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:41:53.610  1507  4285 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:41:53.610  1507  4285 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-12 13:41:53.610  1507  4285 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-12 13:41:56.185  3837  4304 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-12 13:41:56.186  3837  4301 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-12 13:41:56.189  3837  4301 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:41:56.189  3837  4304 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 13:41:56.191  3837  4301 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:41:56.193  3837  4301 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:41:56.191  3837  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:41:56.196  3837  4306 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
09-12 13:41:56.196  3837  4301 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:41:56.196  3837  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:41:56.198  3837  4304 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 13:41:56.202  3837  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
,09-12 13:41:56.203  3837  4307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver),
,09-12 13:41:56.204  3837  4307 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-12 13:41:56.204  3837  4307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 13:41:56.204  3837  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: IncomingSocketThread/Sender)
09-12 13:41:56.208  3837  4309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Receiver)
09-12 13:41:56.210  3837  4309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: IncomingSocketThread/Receiver)
09-12 13:41:56.210  3837  4309 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-12 13:41:56.211  3837  4309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 13:41:56.827  1507  1507 I ConfigService: onDestroy
,09-12 13:41:58.641   873  1317 D ConnectivityService: handlePromptUnvalidated 102
,09-12 13:41:59.186  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 13:41:59.190  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:41:59.197  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7ccb951 Bundle[{}]
,09-12 13:41:59.197  3837  3887 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 13:41:59.198  3837  3887 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 13:41:59.198  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:41:59.199  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:41:59.199  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
09-12 13:41:59.200  3837  3887 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:41:59.204  3837  3887 I System.out: Running OutgoingSocketThread
,09-12 13:41:59.207  3837  4310 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-12 13:41:59.208  3837  4310 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:42:02.217  3837  4311 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-12 13:42:02.217  3837  4311 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-12 13:42:02.218  3837  4310 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-12 13:42:02.218  3837  4311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:42:02.218  3837  4310 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-12 13:42:02.219  3837  4310 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:42:02.219  3837  4311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-12 13:42:02.221  3837  4310 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:42:02.226  3837  4313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
,09-12 13:42:02.228  3837  4311 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-12 13:42:02.230  3837  4310 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-12 13:42:02.231  3837  4314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Sender)
,09-12 13:42:02.236  3837  4315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Receiver)
,09-12 13:42:02.239  3837  4315 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: IncomingSocketThread/Receiver)
,09-12 13:42:02.239  3837  4315 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-12 13:42:02.240  3837  4315 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-12 13:42:02.245  3837  4316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
,09-12 13:42:02.246  3837  4316 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
09-12 13:42:02.247  3837  4316 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-12 13:42:02.248  3837  4316 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-12 13:42:05.220  3837  3887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,09-12 13:42:05.222  3837  3887 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 13:42:05.222  3837  3887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-12 13:42:05.229  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:42:05.229  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ded9c0b added. We now have 3 listener(s)
,09-12 13:42:05.231  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:42:05.231  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:42:05.231  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:42:05.231  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:42:05.231  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38fae8 added. We now have 4 listener(s)
09-12 13:42:05.231  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:42:05.232  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:42:05.235  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:42:05.247  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:42:05.253  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:42:05.253  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:42:05.255  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:42:05.256  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:42:05.259  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:42:05.259  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:42:05.259  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:05.259  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:05.259  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:05.259  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:42:05.259  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ded9c0b removed from the list
09-12 13:42:05.259  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:05.259  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38fae8 removed from the list
09-12 13:42:05.264  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:42:05.265  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:42:05.265  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:05.265  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:05.265  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:05.266  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:05.266  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:05.266  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:05.266  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38fae8 not in the list
,09-12 13:42:05.266  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:05.267  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:05.267  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:05.267  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:05.267  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:05.268  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38fae8 not in the list,
09-12 13:42:05.268  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:05.268  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:05.268  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:05.268  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ded9c0b not in the list
09-12 13:42:05.269  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:42:05.269  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffa8fa6 added. We now have 3 listener(s)
09-12 13:42:05.271  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:42:05.271  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:42:05.271  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:42:05.271  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:42:05.271  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d7ede7 added. We now have 4 listener(s)
09-12 13:42:05.271  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:42:05.272  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:42:05.277  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:42:05.285  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:42:05.289  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-12 13:42:05.289  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:42:05.290  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:42:05.290  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:42:05.290  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:42:05.290  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:42:05.290  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:42:05.294  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:42:05.294  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:42:05.295  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:42:05.299  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:42:05.299  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:42:05.300  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:42:05.301  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:42:05.308  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:42:05.309  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:42:05.309  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:42:05.311  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:42:05.317  4205  4241 D BtGatt.GattService: registerClient() - UUID=f3ff0e9e-93eb-4051-b19b-d98d0f4f0bdf
,09-12 13:42:05.319  4205  4221 D BtGatt.GattService: onClientRegistered() - UUID=f3ff0e9e-93eb-4051-b19b-d98d0f4f0bdf, clientIf=5
,09-12 13:42:05.319  3837  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:42:05.321  4205  4244 D BtGatt.GattService: start scan with filters
,09-12 13:42:05.325  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:42:05.325  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:42:05.326  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:42:05.326  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:42:05.326  4205  4224 D BtGatt.ScanManager: handling starting scan
,09-12 13:42:05.331  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:42:05.331  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:42:05.331  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:42:05.332  4205  4224 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@509a4d5
,09-12 13:42:05.334  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:42:05.339  3837  3887 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:42:05.339  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:42:05.340  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:42:05.340  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:05.340  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:42:05.340  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:42:05.340  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:42:05.340  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:42:05.341  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:42:05.341  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:42:05.341  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:42:05.343  3837  3887 D BluetoothAdapter: STATE_ON
09-12 13:42:05.344  4205  4241 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:42:05.345  4205  4244 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:42:05.348  4205  4221 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:42:05.348  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:05.349  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:42:05.349  4205  4224 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:42:05.349  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:42:05.349  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:42:05.352  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:42:05.352  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:42:05.357  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:42:05.357  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:42:05.357  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:42:05.357  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:42:05.359  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:05.361  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:42:05.361  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:42:05.361  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:42:05.366  4205  4221 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:42:05.366  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:05.367  4205  4224 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:42:05.367  4205  4224 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:42:05.380  4205  4221 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:42:05.381  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:05.390  4205  4221 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:42:05.390  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:05.405  4205  4221 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:42:05.405  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:05.405  4205  4224 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:42:05.415  4205  4221 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:42:05.415  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:05.415  4205  4224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:42:05.423  4205  4221 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 13:42:05.424  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-12 13:42:05.862  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:42:05.862  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:42:05.863  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:42:08.362  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:42:08.363  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:42:08.363  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:42:08.364  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:42:08.364  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:08.364  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:08.365  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:42:08.365  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffa8fa6 removed from the list
09-12 13:42:08.365  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:08.366  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d7ede7 removed from the list
09-12 13:42:08.366  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:42:08.366  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:08.368  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:08.368  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:42:08.372  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:42:08.372  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:42:08.372  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:08.373  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d7ede7 not in the list
09-12 13:42:08.373  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:08.373  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:42:08.376  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:08.376  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:42:08.377  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:08.377  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d7ede7 not in the list
,09-12 13:42:08.377  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:08.378  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:08.378  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:08.378  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ffa8fa6 not in the list
,09-12 13:42:08.380  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:42:08.380  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e3f00 added. We now have 3 listener(s)
,09-12 13:42:08.382  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:42:08.382  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:42:08.383  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:42:08.383  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:42:08.383  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a830339 added. We now have 4 listener(s)
09-12 13:42:08.383  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:42:08.383  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:42:08.387  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:42:08.394  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:42:08.397  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:42:08.397  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:42:08.397  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:42:08.398  3837  3887 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-12 13:42:08.398  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-12 13:42:08.400  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-12 13:42:08.401  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-12 13:42:08.401  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:42:08.401  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:42:08.402  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:42:08.402  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 13:42:08.402  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-12 13:42:08.402  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-12 13:42:08.402  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-12 13:42:08.403  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:42:08.403  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:42:08.404  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:42:08.407  3837  4317 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:42:08.411  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:42:08.411  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:42:08.415  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:42:08.415  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:42:08.415  3837  4317 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-12 13:42:08.418  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:42:08.419  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:42:08.419  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:42:08.421  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-12 13:42:08.422  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:42:08.422  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-12 13:42:08.423  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-12 13:42:08.423  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-12 13:42:08.423  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-12 13:42:08.424  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:42:08.427  4205  4232 D BtGatt.GattService: registerClient() - UUID=b185a795-326b-43b5-a720-3a39afb1ef20
,09-12 13:42:08.428  4205  4221 D BtGatt.GattService: onClientRegistered() - UUID=b185a795-326b-43b5-a720-3a39afb1ef20, clientIf=5
09-12 13:42:08.428  3837  3848 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-12 13:42:08.430  4205  4223 D BtGatt.AdvertiseManager: message : 0
,09-12 13:42:08.433  4205  4223 D BtGatt.AdvertiseManager: starting multi advertising
,09-12 13:42:08.445  4205  4221 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-12 13:42:08.453  4205  4221 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-12 13:42:08.454  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-12 13:42:08.455  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:42:08.457  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:42:08.458  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-12 13:42:08.458  3837  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-12 13:42:08.459  3837  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-12 13:42:08.459  3837  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-12 13:42:08.459  3837  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-12 13:42:08.459  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-12 13:42:08.462  3837  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-12 13:42:08.462  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-12 13:42:08.462  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:42:08.463  3837  3887 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:42:08.963  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-12 13:42:11.464  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:42:11.465  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-12 13:42:11.465  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:42:11.465  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-12 13:42:11.466  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:42:11.466  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-12 13:42:11.467  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:42:11.467  3837  4317 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:42:11.467  3837  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 13:42:11.467  3837  4317 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:42:11.467  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:42:11.467  3837  4317 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:42:11.467  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:42:11.468  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:42:11.468  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:42:11.468  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:42:11.469  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:42:11.471  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:42:11.471  3837  3887 D BluetoothLeScanner: could not find callback wrapper
09-12 13:42:11.472  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:42:11.472  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,09-12 13:42:11.474  4205  4223 D BtGatt.AdvertiseManager: message : 1
09-12 13:42:11.476  4205  4223 D BtGatt.AdvertiseManager: stop advertise for client 5
09-12 13:42:11.487  4205  4221 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-12 13:42:11.487  4205  4221 D BtGatt.GattService: Client app is not null!
09-12 13:42:11.490  4205  4216 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:42:11.491  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:42:11.492  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-12 13:42:11.492  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-12 13:42:11.493  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-12 13:42:11.493  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-12 13:42:11.496  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:42:11.496  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:42:11.496  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:42:11.497  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:42:11.500  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:42:11.500  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:42:11.501  3837  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:42:11.501  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:42:11.501  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:42:11.501  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:42:11.502  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:42:11.502  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:11.503  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:11.503  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:42:11.503  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e3f00 removed from the list
,09-12 13:42:11.504  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:11.504  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a830339 removed from the list
09-12 13:42:11.504  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:42:11.504  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:11.506  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:11.506  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:11.508  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:42:11.509  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:11.509  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:11.509  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a830339 not in the list
09-12 13:42:11.510  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:11.510  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:42:11.512  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:42:11.512  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:11.513  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:11.513  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a830339 not in the list
09-12 13:42:11.513  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:11.513  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:42:11.514  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:11.514  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e3f00 not in the list
,09-12 13:42:11.517  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:42:11.518  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3638a added. We now have 3 listener(s)
,09-12 13:42:11.525  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:42:11.526  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:42:11.526  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:42:11.526  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:42:11.527  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a19dfb added. We now have 4 listener(s)
,09-12 13:42:11.527  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:42:11.528  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:42:11.532  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:42:11.538  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:42:11.542  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:42:11.542  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:42:11.543  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:42:11.543  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:42:11.543  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:42:11.543  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:42:11.543  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:42:11.547  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:42:11.549  3837  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:42:11.549  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:42:11.554  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:42:11.555  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:42:11.556  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 13:42:11.556  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:42:11.560  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:42:11.561  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:42:11.561  3837  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:42:11.562  3837  3887 D BluetoothAdapter: STATE_ON
,09-12 13:42:11.566  4205  4244 D BtGatt.GattService: registerClient() - UUID=faed975a-e4e1-47e7-baab-2670a850d6c8
,09-12 13:42:11.566  4205  4221 D BtGatt.GattService: onClientRegistered() - UUID=faed975a-e4e1-47e7-baab-2670a850d6c8, clientIf=5
09-12 13:42:11.566  3837  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:42:11.567  4205  4232 D BtGatt.GattService: start scan with filters
,09-12 13:42:11.571  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:42:11.572  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:42:11.572  4205  4224 D BtGatt.ScanManager: handling starting scan
09-12 13:42:11.572  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:42:11.572  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:42:11.577  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:42:11.577  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:42:11.578  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:42:11.580  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:42:11.589  4205  4221 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 13:42:11.589  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:42:11.590  4205  4224 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:42:11.600  4205  4221 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:42:11.600  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:42:11.600  4205  4224 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:42:11.600  4205  4224 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:42:11.621  4205  4221 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 13:42:11.621  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:11.631  4205  4221 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 13:42:11.631  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:12.002  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:42:12.079  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-12 13:42:12.079  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:42:12.079  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:42:13.138  4205  4205 D BtGatt.ScanManager: awakened up at time 234319
,09-12 13:42:13.140  4205  4224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:42:13.197  4205  4221 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-12 13:42:13.197  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:13.198  4205  4221 D BtGatt.GattService: current time is 234379478219
,09-12 13:42:13.199  4205  4221 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -98, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -92, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -99, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91],
,09-12 13:42:13.203  4205  4221 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-12 13:42:13.205  4205  4221 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-12 13:42:13.206  4205  4221 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-12 13:42:13.207  4205  4221 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 13:42:13.207  4205  4221 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:42:13.208  4205  4221 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-12 13:42:14.594  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:42:14.594  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:42:14.594  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:42:14.595  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.595  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-12 13:42:14.596  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:42:14.596  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:42:14.597  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:42:14.597  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:42:14.597  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:42:14.598  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:42:14.601  3837  3887 D BluetoothAdapter: STATE_ON
09-12 13:42:14.603  4205  4241 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:42:14.605  4205  4244 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:42:14.606  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:42:14.606  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:42:14.607  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:42:14.607  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:42:14.608  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:42:14.614  4205  4205 D BtGatt.ScanManager: awakened up at time 235795
,09-12 13:42:14.614  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-12 13:42:14.614  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:42:14.615  3837  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:42:14.615  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:42:14.617  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:14.622  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:42:14.622  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:42:14.622  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:42:14.623  4205  4221 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:42:14.623  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:42:14.624  4205  4224 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:42:14.624  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:14.624  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.624  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:14.624  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-12 13:42:14.625  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3638a removed from the list
09-12 13:42:14.625  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:14.626  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a19dfb removed from the list
09-12 13:42:14.626  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:42:14.626  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:14.627  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.627  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:14.628  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:14.628  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:14.628  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:14.628  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a19dfb not in the list
09-12 13:42:14.628  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.628  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:14.630  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:14.630  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:14.630  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:14.630  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a19dfb not in the list
09-12 13:42:14.630  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:14.630  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.630  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:42:14.630  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3638a not in the list
09-12 13:42:14.631  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:42:14.631  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976d3c4 added. We now have 3 listener(s)
09-12 13:42:14.633  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:42:14.633  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:42:14.633  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:42:14.634  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:42:14.634  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b612ad added. We now have 4 listener(s)
,09-12 13:42:14.634  3837  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:42:14.634  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:42:14.639  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:42:14.640  4205  4221 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:42:14.640  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:14.641  4205  4224 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:42:14.645  3837  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:42:14.648  3837  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:42:14.649  3837  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:42:14.649  3837  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:42:14.650  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:42:14.650  3837  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:42:14.650  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:14.651  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:42:14.651  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:42:14.651  3837  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:42:14.651  3837  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976d3c4 removed from the list
09-12 13:42:14.651  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:14.651  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:42:14.652  3837  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b612ad removed from the list,
09-12 13:42:14.654  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:42:14.655  4205  4221 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:42:14.655  4205  4221 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:42:14.655  3837  3887 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:42:14.657  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:42:14.658  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.658  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-12 13:42:14.659  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:14.660  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:42:14.660  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:14.660  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b612ad not in the list
09-12 13:42:14.660  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.660  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:42:14.662  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:42:14.662  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:42:14.662  3837  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:42:14.662  3837  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b612ad not in the list
09-12 13:42:14.663  3837  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:42:14.663  3837  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:42:14.663  3837  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:42:14.663  3837  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@976d3c4 not in the list
,09-12 13:42:14.665  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:42:14.665  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 13:42:14.666  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:42:14.666  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:42:14.666  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:42:14.667  3837  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:42:15.124  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:42:16.686  3837  4319 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-12 13:42:18.684  3837  3887 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 459
,09-12 13:42:18.684  3837  3887 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 459, name: My test thread name)
,09-12 13:42:18.690  3837  4320 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-12 13:42:18.691  3837  4320 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
,09-12 13:42:18.691  3837  4320 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-12 13:42:18.695  3837  3887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-12 13:42:18.704  3837  4321 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,09-12 13:42:18.705  3837  4321 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 464, thread name: My test thread name): Test exception.
,09-12 13:42:18.706  3837  4321 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-12 13:42:18.714  3837  3887 I jxcore-log: Total number of executed tests:  82
09-12 13:42:18.714  3837  3887 I jxcore-log: 
,09-12 13:42:18.715  3837  3887 I jxcore-log: Number of passed tests:  82
09-12 13:42:18.715  3837  3887 I jxcore-log: 
09-12 13:42:18.716  3837  3887 I jxcore-log: Number of failed tests:  0
09-12 13:42:18.716  3837  3887 I jxcore-log: 
,09-12 13:42:18.717  3837  3887 I jxcore-log: Number of ignored tests:  0
09-12 13:42:18.717  3837  3887 I jxcore-log: 
,09-12 13:42:18.717  3837  3887 I jxcore-log: Total duration:  101332
09-12 13:42:18.717  3837  3887 I jxcore-log: 
,09-12 13:42:18.726  3837  3887 I jxcore-log: Unit Test app is loaded
09-12 13:42:18.726  3837  3887 I jxcore-log: 
,09-12 13:42:18.735  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.735  3837  3887 I jxcore-log: 
,09-12 13:42:18.741  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.741  3837  3887 I jxcore-log: 
,09-12 13:42:18.742  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-12 13:42:18.742  3837  3887 I jxcore-log: 
,09-12 13:42:18.743  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.743  3837  3887 I jxcore-log: 
09-12 13:42:18.745  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 13:42:18.745  3837  3887 I jxcore-log: 
,09-12 13:42:18.745  3837  3837 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 13:42:18.747  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:42:18.747  3837  3887 I jxcore-log: 
09-12 13:42:18.745  3837  4319 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-12 13:42:18.749  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.749  3837  3887 I jxcore-log: 
,09-12 13:42:18.752  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.752  3837  3887 I jxcore-log: 
09-12 13:42:18.753  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 13:42:18.753  3837  3887 I jxcore-log: 
,09-12 13:42:18.754  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:42:18.754  3837  3887 I jxcore-log: 
09-12 13:42:18.755  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:42:18.755  3837  3887 I jxcore-log: 
,09-12 13:42:18.756  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.756  3837  3887 I jxcore-log: 
09-12 13:42:18.756  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.756  3837  3887 I jxcore-log: 
,09-12 13:42:18.757  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.757  3837  3887 I jxcore-log: 
09-12 13:42:18.758  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.758  3837  3887 I jxcore-log: 
,09-12 13:42:18.759  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.759  3837  3887 I jxcore-log: 
09-12 13:42:18.760  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.760  3837  3887 I jxcore-log: 
,09-12 13:42:18.761  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.761  3837  3887 I jxcore-log: 
09-12 13:42:18.762  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.762  3837  3887 I jxcore-log: ,
09-12 13:42:18.762  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.762  3837  3887 I jxcore-log: 
09-12 13:42:18.763  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.763  3837  3887 I jxcore-log: 
,09-12 13:42:18.764  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.764  3837  3887 I jxcore-log: 
09-12 13:42:18.765  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.765  3837  3887 I jxcore-log: 
,09-12 13:42:18.766  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.766  3837  3887 I jxcore-log: 
09-12 13:42:18.767  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.767  3837  3887 I jxcore-log: ,
09-12 13:42:18.767  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.767  3837  3887 I jxcore-log: 
09-12 13:42:18.768  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.768  3837  3887 I jxcore-log: 
,09-12 13:42:18.768  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.768  3837  3887 I jxcore-log: 
09-12 13:42:18.769  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.769  3837  3887 I jxcore-log: 
09-12 13:42:18.769  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-12 13:42:18.769  3837  3887 I jxcore-log: 
09-12 13:42:18.770  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.770  3837  3887 I jxcore-log: 
09-12 13:42:18.770  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.770  3837  3887 I jxcore-log: ,
09-12 13:42:18.771  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.771  3837  3887 I jxcore-log: 
09-12 13:42:18.771  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.771  3837  3887 I jxcore-log: 
,09-12 13:42:18.772  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.772  3837  3887 I jxcore-log: 
09-12 13:42:18.772  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.772  3837  3887 I jxcore-log: 
09-12 13:42:18.773  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.773  3837  3887 I jxcore-log: ,
09-12 13:42:18.773  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.773  3837  3887 I jxcore-log: 
09-12 13:42:18.774  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.774  3837  3887 I jxcore-log: 
,09-12 13:42:18.774  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.774  3837  3887 I jxcore-log: 
09-12 13:42:18.775  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:42:18.775  3837  3887 I jxcore-log: 
09-12 13:42:18.775  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.775  3837  3887 I jxcore-log: 
,09-12 13:42:18.776  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:42:18.776  3837  3887 I jxcore-log: 
09-12 13:42:18.776  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.776  3837  3887 I jxcore-log: 
09-12 13:42:18.777  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-12 13:42:18.777  3837  3887 I jxcore-log: 
09-12 13:42:18.777  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.777  3837  3887 I jxcore-log: 
09-12 13:42:18.778  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.778  3837  3887 I jxcore-log: 
,09-12 13:42:18.778  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.778  3837  3887 I jxcore-log: 
09-12 13:42:18.779  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:42:18.779  3837  3887 I jxcore-log: 
09-12 13:42:18.779  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,09-12 13:42:18.779  3837  3887 I jxcore-log: 
09-12 13:42:18.780  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-12 13:42:18.780  3837  3887 I jxcore-log: 
09-12 13:42:18.780  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.780  3837  3887 I jxcore-log: 
,09-12 13:42:18.781  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:42:18.781  3837  3887 I jxcore-log: 
09-12 13:42:18.781  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-12 13:42:18.781  3837  3887 I jxcore-log: 
09-12 13:42:18.782  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:42:18.782  3837  3887 I jxcore-log: 
,09-12 13:42:18.782  3837  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:42:18.782  3837  3887 I jxcore-log: 
,09-12 13:42:18.787  3837  3887 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
,09-12 13:42:18.787  3837  3887 I jxcore-log:   bluetooth: 'on',
09-12 13:42:18.787  3837  3887 I jxcore-log:   wifi: 'on',
09-12 13:42:18.787  3837  3887 I jxcore-log:   cellular: 'doNotCare',
09-12 13:42:18.787  3837  3887 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 13:42:18.787  3837  3887 I jxcore-log: 
,09-12 13:42:18.792  3837  3887 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
,09-12 13:42:18.792  3837  3887 I jxcore-log:   bluetooth: 'on',
09-12 13:42:18.792  3837  3887 I jxcore-log:   wifi: 'on',
09-12 13:42:18.792  3837  3887 I jxcore-log:   cellular: 'doNotCare',
09-12 13:42:18.792  3837  3887 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-12 13:42:18.792  3837  3887 I jxcore-log: 
09-12 13:42:18.793  3837  3887 I jxcore-log: My device name is: motorola-Nexus 6
09-12 13:42:18.793  3837  3887 I jxcore-log: 
,09-12 13:42:18.793  3837  3887 I jxcore-log: Running for WIFI network type
09-12 13:42:18.793  3837  3887 I jxcore-log: 
,09-12 13:42:21.386  3837  3887 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThatAlwaysPass.js
09-12 13:42:21.386  3837  3887 I jxcore-log: 
,09-12 13:42:21.398  3837  3887 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-12 13:42:21.400  3837  3887 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
,09-12 13:42:21.400  3837  3887 I jxcore-log: 
,09-12 13:42:21.402  3837  3887 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-12 13:42:21.402  3837  3887 I jxcore-log: 
09-12 13:42:21.403  3837  3887 I jxcore-log: ThaliTape :: Started ThaliTape
09-12 13:42:21.403  3837  3887 I jxcore-log: 
,09-12 13:42:21.407  3837  3887 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-12 13:42:21.407  3837  3887 I jxcore-log: 
,09-12 13:42:21.497  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:21.497  3837  3887 I jxcore-log: 
,09-12 13:42:21.498  3837  3887 I jxcore-log: websocket error
09-12 13:42:21.498  3837  3887 I jxcore-log: 
09-12 13:42:21.498  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:21.498  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:21.498  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:21.498  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:21.498  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:21.498  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:21.498  3837  3887 I jxcore-log: 
,09-12 13:42:22.657  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:22.657  3837  3887 I jxcore-log: 
,09-12 13:42:22.659  3837  3887 I jxcore-log: websocket error
09-12 13:42:22.659  3837  3887 I jxcore-log: 
,09-12 13:42:22.659  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:22.659  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:22.659  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:22.659  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:22.659  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:22.659  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:22.659  3837  3887 I jxcore-log: 
,09-12 13:42:23.649  3804  4322 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 13:42:23.672  3804  4323 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 13:42:23.702  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:42:23.707  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:42:23.750  1507  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 13:42:23.751  1507  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 13:42:23.751  1507  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:42:23.751  1507  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:42:23.797  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:42:23.800  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:42:23.833  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-12 13:42:23.834  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-12 13:42:23.834  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:42:23.834  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:42:23.858  3804  4323 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 13:42:23.860  3804  4322 E BooksSync: Soft error
09-12 13:42:23.860  3804  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:42:23.860  3804  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 13:42:23.861  3804  4322 E BooksSync: Sync error
09-12 13:42:23.861  3804  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:42:23.861  3804  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 13:42:23.861  3804  4322 I BooksSync: Finished books sync
,09-12 13:42:23.874   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 244748, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:42:24.693  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:24.693  3837  3887 I jxcore-log: 
,09-12 13:42:24.693  3837  3887 I jxcore-log: websocket error
09-12 13:42:24.693  3837  3887 I jxcore-log: 
,09-12 13:42:24.693  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:24.693  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:24.693  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:24.693  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:24.693  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:24.693  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:24.693  3837  3887 I jxcore-log: 
,09-12 13:42:28.596  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:28.596  3837  3887 I jxcore-log: 
,09-12 13:42:28.596  3837  3887 I jxcore-log: websocket error
09-12 13:42:28.596  3837  3887 I jxcore-log: 
,09-12 13:42:28.597  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:28.597  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:28.597  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:28.597  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:28.597  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:28.597  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:28.597  3837  3887 I jxcore-log: 
,09-12 13:42:33.653  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:33.653  3837  3887 I jxcore-log: 
,09-12 13:42:33.653  3837  3887 I jxcore-log: websocket error
09-12 13:42:33.653  3837  3887 I jxcore-log: 
,09-12 13:42:33.653  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:33.653  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:33.653  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:33.653  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:33.653  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:33.653  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:33.653  3837  3887 I jxcore-log: 
,09-12 13:42:38.283   873  4261 D NetlinkSocketObserver: NeighborEvent{elapsedMs=259463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 13:42:38.714  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:38.714  3837  3887 I jxcore-log: 
,09-12 13:42:38.714  3837  3887 I jxcore-log: websocket error,
09-12 13:42:38.714  3837  3887 I jxcore-log: 
,09-12 13:42:38.714  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:38.714  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:38.714  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:38.714  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:38.714  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:38.714  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:38.714  3837  3887 I jxcore-log: 
,09-12 13:42:43.697   873  4261 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-12 13:42:43.765  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:43.765  3837  3887 I jxcore-log: 
,09-12 13:42:43.765  3837  3887 I jxcore-log: websocket error
09-12 13:42:43.765  3837  3887 I jxcore-log: 
09-12 13:42:43.765  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:43.765  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:43.765  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:43.765  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:43.765  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:43.765  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:43.765  3837  3887 I jxcore-log: 
,09-12 13:42:49.012  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:49.012  3837  3887 I jxcore-log: 
,09-12 13:42:49.013  3837  3887 I jxcore-log: websocket error
09-12 13:42:49.013  3837  3887 I jxcore-log: 
09-12 13:42:49.013  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:49.013  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:49.013  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:49.013  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:49.013  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:49.013  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:49.013  3837  3887 I jxcore-log: 
,09-12 13:42:54.061  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:54.061  3837  3887 I jxcore-log: 
,09-12 13:42:54.061  3837  3887 I jxcore-log: websocket error
09-12 13:42:54.061  3837  3887 I jxcore-log: 
,09-12 13:42:54.062  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:54.062  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:54.062  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:54.062  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:54.062  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:54.062  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:54.062  3837  3887 I jxcore-log: 
,09-12 13:42:54.166  3763  4325 V KeepSync: Connecting to GoogleApiClient
09-12 13:42:54.166   873  2227 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 13:42:54.197  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:42:54.198  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:42:54.214  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 13:42:54.214  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 13:42:54.215  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:42:54.215  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:42:54.231  1736  4326 V BaseAuthAsyncOperation: access token request failed
,09-12 13:42:54.232  3763  4325 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 13:42:54.292  1507  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 13:42:54.292  1507  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 13:42:54.292  1507  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:42:54.292  1507  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:42:54.311  3763  4325 E KeepSync: IOException
09-12 13:42:54.311  3763  4325 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 13:42:54.311  3763  4325 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:42:54.311  3763  4325 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 13:42:54.311  3763  4325 E KeepSync: 	... 10 more
,09-12 13:42:54.311  3763  4325 W KeepSync: Sync result 2
,09-12 13:42:54.328   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 245298, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:42:59.117  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:42:59.117  3837  3887 I jxcore-log: 
09-12 13:42:59.117  3837  3887 I jxcore-log: websocket error
09-12 13:42:59.117  3837  3887 I jxcore-log: 
09-12 13:42:59.117  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:42:59.117  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:42:59.117  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:42:59.117  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:59.117  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:42:59.117  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:42:59.117  3837  3887 I jxcore-log: 
,09-12 13:43:04.217  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:43:04.217  3837  3887 I jxcore-log: 
09-12 13:43:04.217  3837  3887 I jxcore-log: websocket error
09-12 13:43:04.217  3837  3887 I jxcore-log: 
,09-12 13:43:04.218  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:43:04.218  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:43:04.218  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:43:04.218  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:43:04.218  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:43:04.218  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:43:04.218  3837  3887 I jxcore-log: 
,09-12 13:43:09.281  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:43:09.281  3837  3887 I jxcore-log: 
,09-12 13:43:09.281  3837  3887 I jxcore-log: websocket error
09-12 13:43:09.281  3837  3887 I jxcore-log: 
09-12 13:43:09.281  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:43:09.281  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:43:09.281  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:43:09.281  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:43:09.281  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:43:09.281  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:43:09.281  3837  3887 I jxcore-log: 
,09-12 13:43:14.337  3837  3887 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-12 13:43:14.337  3837  3887 I jxcore-log: 
,09-12 13:43:14.338  3837  3887 I jxcore-log: websocket error
09-12 13:43:14.338  3837  3887 I jxcore-log: 
,09-12 13:43:14.339  3837  3887 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-12 13:43:14.339  3837  3887 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-12 13:43:14.339  3837  3887 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-12 13:43:14.339  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:43:14.339  3837  3887 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-12 13:43:14.339  3837  3887 I jxcore-log: emit@events.js:82:1
09-12 13:43:14.339  3837  3887 I jxcore-log: 
,09-12 13:43:20.116  3837  3887 I jxcore-log: ThaliTape :: Reconnected to the test server
09-12 13:43:20.116  3837  3887 I jxcore-log: 
,09-12 13:43:20.130  3837  3887 I jxcore-log: ThaliTape :: Connected to the test server
09-12 13:43:20.130  3837  3887 I jxcore-log: 
,09-12 13:43:24.716  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:43:24.720  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:43:24.759  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:43:24.759  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 13:43:24.759  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:43:24.759  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:43:24.788  3593  4342 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 13:43:24.788  3593  4342 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at blb.a(PG:3937)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at czp.a(PG:18188)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:43:24.788  3593  4342 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	... 12 more
09-12 13:43:24.788  3593  4342 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at fal.a(PG:38)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:43:24.788  3593  4342 E HttpOperation: 	... 14 more
,09-12 13:43:24.880  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:43:24.880  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 13:43:24.880  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:43:24.880  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:43:24.897  3593  4342 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 13:43:24.897  3593  4342 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at hec.a(PG:42)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at hee.a(PG:102)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at czr.a(PG:65)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at kka.a(PG:108)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at czp.a(PG:19176)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:43:24.897  3593  4342 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	... 15 more
09-12 13:43:24.897  3593  4342 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at fal.a(PG:38)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:43:24.897  3593  4342 E HttpOperation: 	... 17 more
,09-12 13:43:24.897  3593  4342 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 13:43:24.897  3593  4342 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at hec.a(PG:42)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at hee.a(PG:102)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at czr.a(PG:65)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at kka.a(PG:108)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	... 15 more
09-12 13:43:24.897  3593  4342 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at fal.a(PG:38)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 13:43:24.897  3593  4342 E ExperimentLoader: 	... 17 more
,09-12 13:43:25.013   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 280064, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:43:55.252  3804  4346 I BooksSync: Starting books sync for 61035162, extras: ade
,09-12 13:43:55.266  3804  4347 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-12 13:43:55.276  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:43:55.278  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:43:55.296  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 13:43:55.296  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 13:43:55.296  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:43:55.296  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:43:55.317  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:43:55.318  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:43:55.335  1507  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-12 13:43:55.336  1507  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-12 13:43:55.336  1507  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:43:55.336  1507  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:43:55.348  3804  4347 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-12 13:43:55.349  3804  4346 E BooksSync: Soft error
09-12 13:43:55.349  3804  4346 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:43:55.349  3804  4346 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-12 13:43:55.349  3804  4346 E BooksSync: Sync error
09-12 13:43:55.349  3804  4346 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-12 13:43:55.349  3804  4346 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-12 13:43:55.349  3804  4346 I BooksSync: Finished books sync
,09-12 13:43:55.363   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309463, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:44:24.892  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:44:24.900  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:44:24.901  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:44:24.924  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-12 13:44:24.924  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-12 13:44:24.924  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:44:24.924  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:44:24.950  1507  2288 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-12 13:44:24.950  1507  2288 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-12 13:44:24.950  1507  2288 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-12 13:44:24.950  1507  2288 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-12 13:44:24.950  1507  2288 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-12 13:44:24.950  1507  2288 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-12 13:44:24.950  1507  2288 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 13:44:24.955  3549  3585 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-12 13:44:24.955  3549  3585 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-12 13:44:24.955  3549  3585 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-12 13:44:24.955  3549  3585 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-12 13:44:24.955  3549  3585 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-12 13:44:24.955  3549  3585 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-12 13:44:24.955  3549  3585 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-12 13:44:25.649  3763  4354 V KeepSync: Connecting to GoogleApiClient
,09-12 13:44:25.653   873  2233 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 13:44:25.743  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:44:25.743  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-12 13:44:25.743  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:44:25.743  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:44:25.812  3593  4353 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 13:44:25.812  3593  4353 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at blb.a(PG:3937)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at czp.a(PG:18188)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:44:25.812  3593  4353 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	... 12 more
09-12 13:44:25.812  3593  4353 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at fal.a(PG:38)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:44:25.812  3593  4353 E HttpOperation: 	... 14 more
,09-12 13:44:25.943  1507  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:44:25.944  1507  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 13:44:25.944  1507  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:44:25.944  1507  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:44:25.944  1507  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 13:44:25.945  1507  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 13:44:25.945  1507  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:44:25.945  1507  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:44:26.007  3593  4353 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 13:44:26.007  3593  4353 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at hec.a(PG:42)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at hee.a(PG:102)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at czr.a(PG:65)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at kka.a(PG:108)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at czp.a(PG:19176)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:44:26.007  3593  4353 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	... 15 more
09-12 13:44:26.007  3593  4353 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at fal.a(PG:38)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:44:26.007  3593  4353 E HttpOperation: 	... 17 more
09-12 13:44:26.009  3593  4353 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 13:44:26.009  3593  4353 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at hec.a(PG:42)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at hee.a(PG:102)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at czr.a(PG:65)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at kka.a(PG:108)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	... 15 more
09-12 13:44:26.009  3593  4353 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at fal.a(PG:38)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 13:44:26.009  3593  4353 E ExperimentLoader: 	... 17 more
,09-12 13:44:26.014  1736  4355 V BaseAuthAsyncOperation: access token request failed
,09-12 13:44:26.015  3763  4354 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 13:44:26.109  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 13:44:26.110  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 13:44:26.110  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:44:26.110  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:44:26.130   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 337918, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:44:26.141  3763  4354 E KeepSync: IOException
09-12 13:44:26.141  3763  4354 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 13:44:26.141  3763  4354 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:44:26.141  3763  4354 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 13:44:26.141  3763  4354 E KeepSync: 	... 10 more
09-12 13:44:26.141  3763  4354 W KeepSync: Sync result 2
,09-12 13:44:26.166   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 340425, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:45:26.628  3837  3887 I jxcore-log: TAP version 13
09-12 13:45:26.628  3837  3887 I jxcore-log: 
,09-12 13:45:26.633  3837  3887 I jxcore-log: # setup
09-12 13:45:26.633  3837  3887 I jxcore-log: 
,09-12 13:45:27.521  3837  3887 I jxcore-log: ok 1 (unnamed assert)
09-12 13:45:27.521  3837  3887 I jxcore-log: 
,09-12 13:45:27.532  3837  3887 I jxcore-log: # 1. The test that always pass
09-12 13:45:27.532  3837  3887 I jxcore-log: 
,09-12 13:45:28.141  3837  3887 I jxcore-log: ok 2 (unnamed assert)
09-12 13:45:28.141  3837  3887 I jxcore-log: 
,09-12 13:45:28.151  3837  3887 I jxcore-log: # teardown
09-12 13:45:28.151  3837  3887 I jxcore-log: 
,09-12 13:45:28.876  3837  3887 I jxcore-log: ok 3 (unnamed assert)
09-12 13:45:28.876  3837  3887 I jxcore-log: 
,09-12 13:45:29.046  3837  3887 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 13:45:29.046  3837  3887 I jxcore-log: 
,09-12 13:45:29.739  4360  4360 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 13:45:29.745  4360  4360 D AndroidRuntime: CheckJNI is OFF
,09-12 13:45:29.782  4360  4360 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 13:45:29.832  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:45:29.834  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:45:29.861  4360  4360 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 13:45:29.866  1507  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 13:45:29.866  1507  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 13:45:29.866  1507  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:45:29.866  1507  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:45:29.880  3593  4363 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 13:45:29.880  3593  4363 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at blb.a(PG:3937)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at czp.a(PG:18188)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:45:29.880  3593  4363 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	... 12 more
09-12 13:45:29.880  3593  4363 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at fal.a(PG:38)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:45:29.880  3593  4363 E HttpOperation: 	... 14 more
,09-12 13:45:29.890  4360  4360 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 13:45:29.900   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-12 13:45:29.901   873   886 I ActivityManager: Killing 3837:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 13:45:29.971   873   896 W PackageSettings: Skipping PackageSetting{3152cae com.example.hello/10273} due to missing metadata
,09-12 13:45:30.008   873   896 I art     : Starting a blocking GC Explicit
,09-12 13:45:30.020   873  1704 D GraphicsStats: Buffer count: 2
,09-12 13:45:30.020   873  1391 I WindowState: WIN DEATH: Window{b32e853 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:45:30.022   873  1316 D WifiService: Client connection lost with reason: 4
,09-12 13:45:30.065   873   896 I art     : Explicit concurrent mark sweep GC freed 44589(2MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 1.031ms total 56.535ms
,09-12 13:45:30.071   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-12 13:45:30.071   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-12 13:45:30.072   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-12 13:45:30.072   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 13:45:30.072   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.072   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.072   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:45:30.072   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:45:30.073   873   886 I ActivityManager:   Force finishing activity ActivityRecord{4a93518 u0 com.test.thalitest/.MainActivity t4}
,09-12 13:45:30.082   873  1704 W ActivityManager: Spurious death for ProcessRecord{ed84b2c 0:com.test.thalitest/u0a0}, curProc for 3837: null
,09-12 13:45:30.090   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 13:45:30.092  4360  4360 I art     : System.exit called, status: 0
09-12 13:45:30.092  4360  4360 I AndroidRuntime: VM exiting with result code 0.
,09-12 13:45:30.097  1507  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-12 13:45:30.097  1507  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 13:45:30.097  1507  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:45:30.097  1507  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:45:30.108   873   896 I ActivityManager: Start proc 4374:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-12 13:45:30.109   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 13:45:30.125   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 13:45:30.132  1887  1887 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-12 13:45:30.133  4205  4205 D BluetoothMapAppObserver: onReceive
,09-12 13:45:30.133  4205  4205 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-12 13:45:30.134  2026  2313 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:45:30.139  3641  3641 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-12 13:45:30.151   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:45:30.164  1887  4386 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 13:45:30.177  1949  1949 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 13:45:30.179  1887  4386 I Decoder : createOrResetDecoder
,09-12 13:45:30.199   873  2233 I ActivityManager: Start proc 4390:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 13:45:30.203  1507  1507 I ConfigService: onCreate
,09-12 13:45:30.207  3593  4363 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 13:45:30.207  3593  4363 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jdm.a(PG:82)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jcs.o(PG:406)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jcn.a(PG:1379)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jcs.i(PG:143)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at hec.a(PG:42)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at hee.a(PG:102)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at czr.a(PG:65)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at kka.a(PG:108)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at czp.a(PG:19176)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at czp.a(PG:9081)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at czq.run(PG:1686)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:45:30.207  3593  4363 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jdj.a(PG:4091)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jdj.a(PG:1125)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jdm.a(PG:77)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	... 15 more
09-12 13:45:30.207  3593  4363 E HttpOperation: Caused by: faj: BadAuthentication
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at fal.a(PG:38)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	at jdj.a(PG:4089)
09-12 13:45:30.207  3593  4363 E HttpOperation: 	... 17 more
09-12 13:45:30.207  3593  4363 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 13:45:30.207  3593  4363 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at hec.a(PG:42)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at hee.a(PG:102)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at czr.a(PG:65)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at kka.a(PG:108)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	... 15 more
09-12 13:45:30.207  3593  4363 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at fal.a(PG:38)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 13:45:30.207  3593  4363 E ExperimentLoader: 	... 17 more
,09-12 13:45:30.229   873  2234 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3837 uid 10000
,09-12 13:45:30.230  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-12 13:45:30.233  1507  4372 E ClearcutLoggerIntentService: could not write to store: java.io.IOException: Could not end transaction after writing to SQLite
,09-12 13:45:30.237  1507  4402 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 13:45:30.237  1507  4402 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 13:45:30.238  1507  4402 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-12 13:45:30.240  4390  4390 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 13:45:30.242  1507  4402 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-12 13:45:30.250   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 13:45:30.256  1507  4372 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: disk I/O error (code 3850)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 13:45:30.256  1507  4372 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
09-12 13:45:30.261  1887  4386 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 13:45:30.267  1963  2043 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-12 13:45:30.268   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-12 13:45:30.268   873   885 E PackageManager: Failed to write settings, restoring backup
09-12 13:45:30.268   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 13:45:30.268   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 13:45:30.268   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 13:45:30.268   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 13:45:30.268   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 13:45:30.268   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.268   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.268   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:45:30.272   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-12 13:45:30.272   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:45:30.272   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:45:30.272   873   886 E DropBoxManagerService: 	... 13 more
,09-12 13:45:30.280   873  1704 I ActivityManager: Start proc 4404:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 13:45:30.281  1963  2043 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 13:45:30.281  1963  2043 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1963
09-12 13:45:30.281  1963  2043 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.281  1963  2043 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:45:30.282   873  1994 I ActivityManager: Killing 3702:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 13:45:30.281   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 430760, reason: Periodic, SyncResult: stats [ numIoExceptions: 1 numParseExceptions: 1]
,09-12 13:45:30.284   873   885 W AtomicFile: Couldn't rename file /data/system/sync/pending.xml to backup file /data/system/sync/pending.xml.bak
,09-12 13:45:30.285   873   885 W SyncManager: Error writing pending operations
09-12 13:45:30.285   873   885 W SyncManager: java.io.IOException: Couldn't create directory /data/system/sync/pending.xml
09-12 13:45:30.285   873   885 W SyncManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.writePendingOperationsLocked(SyncStorageEngine.java:2629)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.appendPendingOperationLocked(SyncStorageEngine.java:2678)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncStorageEngine.insertIntoPending(SyncStorageEngine.java:1121)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncQueue.add(SyncQueue.java:145)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncQueue.add(SyncQueue.java:109)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncManager.scheduleSyncOperation(SyncManager.java:1112)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncManager.maybeRescheduleSync(SyncManager.java:1216)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledH(SyncManager.java:3072)
09-12 13:45:30.285   873   885 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2241)
09-12 13:45:30.285   873   885 W SyncManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.285   873   885 W SyncManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.285   873   885 W SyncManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:45:30.299  1887  4386 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 13:45:30.301  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-12 13:45:30.301  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 13:45:30.303  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-12 13:45:30.303  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-12 13:45:30.304  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-12 13:45:30.304  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-12 13:45:30.306  1887  4386 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-12 13:45:30.306  1887  4386 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-12 13:45:30.307  1887  4386 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 13:45:30.307  1887  4386 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-12 13:45:30.308  1887  4386 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 13:45:30.308  1887  4386 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 13:45:30.323  4390  4418 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.323  4390  4418 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.323  4390  4418 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:45:30.332   873  1987 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:45:30.333  4390  4390 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 13:45:30.334   873  4420 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:45:30.334   873  4420 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:45:30.334   873  4420 E DropBoxManagerService: 	... 5 more
,09-12 13:45:30.340  1963  2043 I Process : Sending signal. PID: 1963 SIG: 9
,09-12 13:45:30.358   873  2233 I ActivityManager: Start proc 4423:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 13:45:30.360  4390  4422 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 13:45:30.399  4423  4423 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 13:45:30.440  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-12 13:45:30.442  1507  1507 D AndroidRuntime: Shutting down VM
,09-12 13:45:30.443  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:45:30.443  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
09-12 13:45:30.443  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 13:45:30.443  1507  1507 E AndroidRuntime: 	... 8 more
,09-12 13:45:30.449   873  4441 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:45:30.449   873  4441 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:45:30.449   873  4441 E DropBoxManagerService: 	... 5 more
,09-12 13:45:30.454  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
,09-12 13:45:30.478   873  1420 I ActivityManager: Killing 3526:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 13:45:30.487   873  1304 W InputDispatcher: channel '1c664a8 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-12 13:45:30.487   873  1391 D GraphicsStats: Buffer count: 1
,09-12 13:45:30.487   873  1304 E InputDispatcher: channel '1c664a8 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-12 13:45:30.487   873  1391 I WindowState: WIN DEATH: Window{1c664a8 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-12 13:45:30.487   873  1391 W InputDispatcher: Attempted to unregister already unregistered input channel '1c664a8 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-12 13:45:30.513   873  1316 D WifiService: Client connection lost with reason: 4
09-12 13:45:30.515  1736  4439 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@3ce912
,09-12 13:45:30.535  4390  4418 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-12 13:45:30.540  4390  4422 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.540  4390  4422 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:45:30.541  4390  4422 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 13:45:30.541  4390  4422 E AndroidRuntime: Process: android.process.acore, PID: 4390
09-12 13:45:30.541  4390  4422 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207),
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:45:30.541  4390  4422 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:45:30.541  4390  4418 I Process : Sending signal. PID: 4390 SIG: 9
,09-12 13:45:30.555   873  1703 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1963) has died
,09-12 13:45:30.555   873  1703 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-12 13:45:30.557   873  1703 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:45:30.561   873  1990 I ActivityManager: Process com.google.process.gapps (pid 1507) early provider death
,09-12 13:45:30.562   873  1990 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
,09-12 13:45:30.562   873  1990 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerIntentService in 1000ms
,09-12 13:45:30.562   873  1990 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,09-12 13:45:30.562   873  1990 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,09-12 13:45:30.562   873  1990 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,09-12 13:45:30.562   873  1990 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,09-12 13:45:30.564   873  2233 W ActivityManager: Spurious death for ProcessRecord{47a61e1 0:com.google.process.gapps/u0a11}, curProc for 1507: null
,09-12 13:45:30.565   873  1704 I ActivityManager: Process android.process.acore (pid 4390) has died
09-12 13:45:30.565   873  1704 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40997ms
,09-12 13:45:30.567   873  4442 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:45:30.567   873  4442 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:45:30.567   873  4442 E DropBoxManagerService: 	... 5 more
,09-12 13:45:30.582   873   886 I ActivityManager: Start proc 4443:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:45:30.587  1736  1736 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-12 13:45:30.603   873  1391 I ActivityManager: Start proc 4455:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-12 13:45:30.603   283   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
