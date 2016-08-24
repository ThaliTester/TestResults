#### Test 79763830cb90817_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 16:35:52.603  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:35:52.617  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 16:35:52.619  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 16:35:52.669  1522  1998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 16:35:52.669  1522  1998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 16:35:52.669  1522  1998 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:35:52.669  1522  1998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 16:35:52.690  3526  3526 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 16:35:52.690  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 16:35:52.690  3526  3526 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-24 16:35:53.241  3832  3832 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 16:35:53.245  3832  3832 D AndroidRuntime: CheckJNI is OFF
08-24 16:35:53.277  3832  3832 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 16:35:53.357  3832  3832 I Radio-JNI: register_android_hardware_Radio DONE
08-24 16:35:53.381  3832  3832 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 16:35:53.386   871  2188 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 16:35:53.417  1980  1997 W SearchService: Abort, client detached.
08-24 16:35:53.426  1980  1980 I HotwordDetector: Closing mic
08-24 16:35:53.427  1980  2321 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@82544b4
08-24 16:35:53.427  1980  2334 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 16:35:53.439  3832  3832 D AndroidRuntime: Shutting down VM
08-24 16:35:53.489   871  1947 I ActivityManager: Start proc 3841:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 16:35:53.508   374  2336 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 16:35:53.510   374  2336 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 16:35:53.516   374  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 16:35:53.520  1980  2333 I MicroRecognitionRnrImpl: Detection finished
08-24 16:35:53.521  1980  2328 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 16:35:53.583  3841  3841 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 16:35:53.612  3841  3841 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 16:35:53.623  3841  3841 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 958-964)
08-24 16:35:53.623  3841  3841 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:35:53.642  3841  3841 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {55bffe4}
08-24 16:35:53.643  3841  3841 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:35:53.643  3841  3841 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 16:35:53.650  3841  3841 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 16:35:53.652  3841  3841 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 16:35:53.682  3841  3841 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 16:35:53.697  3841  3841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 16:35:53.697  3841  3841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 16:35:53.697  3841  3841 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 16:35:53.697  3841  3841 I Adreno  : Build Date                       : 10/20/15
08-24 16:35:53.697  3841  3841 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 16:35:53.697  3841  3841 I Adreno  : Local Branch                     : M14
08-24 16:35:53.697  3841  3841 I Adreno  : Remote Branch                    : 
08-24 16:35:53.697  3841  3841 I Adreno  : Remote Branch                    : 
08-24 16:35:53.697  3841  3841 I Adreno  : Reconstruct Branch               : 
,08-24 16:35:53.781   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93d9c77:true
,08-24 16:35:53.841  3841  3841 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 16:35:53.861  3841  3841 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola,
,08-24 16:35:53.940  3841  3880 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 16:35:53.955  3841  3866 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 16:35:53.991  3841  3880 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 16:35:54.084   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +644ms
,08-24 16:35:54.094  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-24 16:35:54.203  3841  3841 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3841
,08-24 16:35:54.340   871  2005 I ActivityManager: Killing 3087:com.google.android.talk/u0a61 (adj 15): empty #17
,08-24 16:35:54.388   871  2005 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-24 16:35:54.407  3841  3841 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 16:35:54.514  3841  3882 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1697122000
,08-24 16:35:54.522  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 16:35:54.522  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 16:35:54.522  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 16:35:54.522  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 16:35:54.522  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 16:35:54.522  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c72124b added. We now have 1 listener(s)
,08-24 16:35:54.525  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-24 16:35:54.526  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 16:35:54.527  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:35:54.527  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 16:35:54.531  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b92ae6 added. We now have 1 listener(s)
08-24 16:35:54.532  3841  3882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:35:54.536   871  1305 D WifiService: New client listening to asynchronous messages
,08-24 16:35:54.537  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:35:54.537  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 16:35:54.537  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-24 16:35:54.538  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 16:35:54.538  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 16:35:54.552  3841  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:35:54.553  3841  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 16:35:54.568  3841  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:35:54.568  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:35:54.568  3841  3882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 16:35:54.568  3841  3882 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:35:54.569  3841  3882 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 16:35:54.574  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:35:54.579  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:35:54.589  3841  3841 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 16:35:55.386   871  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 16:35:55.871  3841  3891 W jxcore-log: Initializing JXcore engine
08-24 16:35:55.871  3841  3891 W jxcore-log: JXcore engine is ready
,08-24 16:35:55.905  3891  3891 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-24 16:35:55.905  3891  3891 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11782]" dev="sockfs" ino=11782 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 16:35:55.905  3891  3891 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 16:35:55.909  3891  3891 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26033]" dev="sockfs" ino=26033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 16:35:55.921  3841  3891 W jxcore-log: Starting JXcore engine
,08-24 16:35:55.997  3841  3891 W jxcore-log: Platform android
08-24 16:35:55.997  3841  3891 W jxcore-log: 
,08-24 16:35:55.997  3841  3891 W jxcore-log: Process ARCH arm
08-24 16:35:55.997  3841  3891 W jxcore-log: 
,08-24 16:35:56.184  3841  3891 I jxcore-log: JXcore Cordova bridge is ready!
08-24 16:35:56.184  3841  3891 I jxcore-log: 
,08-24 16:35:56.184  3841  3891 W jxcore-log: JXcore engine is started
,08-24 16:35:56.193  3841  3882 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 16:35:56.197  3841  3841 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 16:35:59.509  3615  3899 V KeepSync: Connecting to GoogleApiClient
08-24 16:35:59.510   871  2188 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 16:35:59.538  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:35:59.540  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:35:59.562  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 16:35:59.562  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 16:35:59.562  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:35:59.562  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:35:59.596  1744  3900 V BaseAuthAsyncOperation: access token request failed
,08-24 16:35:59.597  3615  3899 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 16:35:59.640  1522  1998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 16:35:59.640  1522  1998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 16:35:59.640  1522  1998 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:35:59.640  1522  1998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:35:59.661  3615  3899 E KeepSync: IOException
08-24 16:35:59.661  3615  3899 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 16:35:59.661  3615  3899 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 16:35:59.661  3615  3899 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 16:35:59.661  3615  3899 E KeepSync: 	... 10 more
,08-24 16:35:59.661  3615  3899 W KeepSync: Sync result 2
,08-24 16:35:59.672   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126290, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 16:36:06.202  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 16:36:06.202  3841  3891 I jxcore-log: 
,08-24 16:36:06.205  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 16:36:06.205  3841  3891 I jxcore-log: 
,08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:36:06.215  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:36:06.220  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:36:06.223  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 16:36:06.223  3841  3891 I jxcore-log: 
,08-24 16:36:06.225  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 16:36:06.225  3841  3891 I jxcore-log: 
,08-24 16:36:06.721  3841  3891 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 16:36:06.722  3841  3891 I jxcore-log: Failed to execute UT.
08-24 16:36:06.722  3841  3891 I jxcore-log: 
,08-24 16:36:06.722  3841  3891 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 16:36:06.722  3841  3891 I jxcore-log: 
,08-24 16:36:06.726  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:36:06.726  3841  3891 I jxcore-log: 
,08-24 16:36:06.747  3841  3841 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 16:36:07.432  3906  3906 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 16:36:07.437  3906  3906 D AndroidRuntime: CheckJNI is OFF
,08-24 16:36:07.472  3906  3906 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 16:36:07.512  3906  3906 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 16:36:07.533  3906  3906 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 16:36:07.543   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-24 16:36:07.544   871   884 I ActivityManager: Killing 3841:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-24 16:36:07.590   871  1295 W InputDispatcher: channel '6189167 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-24 16:36:07.590   871  1295 E InputDispatcher: channel '6189167 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-24 16:36:07.610   871  2041 D GraphicsStats: Buffer count: 2
,08-24 16:36:07.611   871   882 I WindowState: WIN DEATH: Window{6189167 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 16:36:07.611   871  1305 D WifiService: Client connection lost with reason: 4
08-24 16:36:07.611   871   882 W InputDispatcher: Attempted to unregister already unregistered input channel '6189167 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,08-24 16:36:07.637   871   884 W ActivityManager: Force removing ActivityRecord{e08dc1c u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-24 16:36:07.675   871   894 W PackageSettings: Skipping PackageSetting{d412ea3 com.example.hello/10273} due to missing metadata
,08-24 16:36:07.722   871  1937 W ActivityManager: Spurious death for ProcessRecord{1d8aac2 0:com.test.thalitest/u0a0}, curProc for 3841: null
,08-24 16:36:07.730   871   894 I art     : Starting a blocking GC Explicit
,08-24 16:36:07.791   871  2005 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3841 uid 10000
,08-24 16:36:07.799  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-24 16:36:07.800   871   894 I art     : Explicit concurrent mark sweep GC freed 45267(2MB) AllocSpace objects, 13(292KB) LOS objects, 33% free, 29MB/43MB, paused 1.075ms total 67.735ms
,08-24 16:36:07.825  1980  1980 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-24 16:36:07.831   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 16:36:07.836  3906  3906 I art     : System.exit called, status: 0
,08-24 16:36:07.836  3906  3906 I AndroidRuntime: VM exiting with result code 0.
,08-24 16:36:07.863  1980  3922 I MicroRecognitionRnrImpl: Starting detection.
,08-24 16:36:07.863   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-24 16:36:07.864  1980  3923 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@b6ead7c
08-24 16:36:07.868   374  3925 I AudioFlinger: AudioFlinger's thread 0xb3380000 ready to run
08-24 16:36:07.868   374  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-24 16:36:07.869  1980  3923 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@b6ead7c
,08-24 16:36:07.879   374  3925 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-24 16:36:07.879   374  3925 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-24 16:36:07.879   374  3925 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-24 16:36:07.885   374  3925 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-24 16:36:07.893  2650  2650 D BluetoothMapAppObserver: onReceive
,08-24 16:36:07.893  2650  2650 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-24 16:36:07.897   871  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 16:36:07.903  2100  2284 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 16:36:07.905  1855  1855 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-24 16:36:07.907  1855  3929 I Keyboard.Facilitator.DecoderInitializer: run()
,08-24 16:36:07.909  1855  3929 I Decoder : createOrResetDecoder
,08-24 16:36:07.945  1915  1915 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 16:36:07.946  3677  3677 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-24 16:36:07.961  1980  1980 I HotwordWorkerImpl: onReady
,08-24 16:36:07.976  1522  1522 I ConfigService: onCreate
,08-24 16:36:07.997  1855  3929 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-24 16:36:08.006  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-24 16:36:08.006   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 16:36:08.007  1522  1522 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-24 16:36:08.007  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
08-24 16:36:08.007  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
08-24 16:36:08.007  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 16:36:08.007  1522  1522 E AndroidRuntime: 	... 8 more
,08-24 16:36:08.010   871  3935 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:36:08.010   871  3935 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:36:08.010   871  3935 E DropBoxManagerService: 	... 5 more
08-24 16:36:08.025   871  3936 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-24 16:36:08.026  3509  3932 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 16:36:08.039  1855  3929 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-24 16:36:08.042  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 16:36:08.042  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-24 16:36:08.052   871  3936 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 16:36:08.052   871  3936 I Adreno  : Build Date                       : 10/20/15
08-24 16:36:08.052   871  3936 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 16:36:08.052   871  3936 I Adreno  : Local Branch                     : M14
08-24 16:36:08.052   871  3936 I Adreno  : Remote Branch                    : 
08-24 16:36:08.052   871  3936 I Adreno  : Remote Branch                    : 
08-24 16:36:08.052   871  3936 I Adreno  : Reconstruct Branch               : 
,08-24 16:36:08.055  1931  2010 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-24 16:36:08.057   871  3936 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 16:36:08.066   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-24 16:36:08.067   871   883 E PackageManager: Failed to write settings, restoring backup
08-24 16:36:08.067   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 16:36:08.067   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 16:36:08.067   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 16:36:08.067   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 16:36:08.067   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 16:36:08.067   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:36:08.067   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:36:08.067   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:36:08.068   871   881 I ActivityManager: Start proc 3938:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-24 16:36:08.069  1931  2010 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 16:36:08.069  1931  2010 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1931
08-24 16:36:08.069  1931  2010 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:36:08.069  1931  2010 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:36:08.070   871  1380 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 16:36:08.072   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-24 16:36:08.072   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 16:36:08.072   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:36:08.072   871   884 E DropBoxManagerService: 	... 13 more
08-24 16:36:08.073   871  3943 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:36:08.073   871  3943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:36:08.073   871  39,43 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:36:08.073   871  3943 E DropBoxManagerService: 	... 5 more
08-24 16:36:08.087  1980  1997 W SearchService: Abort, client detached.
08-24 16:36:08.089  1980  1980 I HotwordDetector: Closing mic
08-24 16:36:08.090  1980  2321 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b6ead7c
08-24 16:36:08.090  1980  3923 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-24 16:36:08.145   374  3925 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-24 16:36:08.146   374  3925 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 16:36:08.149   374  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-24 16:36:08.155  1980  3922 I MicroRecognitionRnrImpl: Detection finished
,08-24 16:36:08.155  1980  2328 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-24 16:36:08.161   871  1381 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 16:36:08.166  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-24 16:36:08.167  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-24 16:36:08.167  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 16:36:08.167  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 16:36:08.168  1855  3929 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 16:36:08.173  1931  1931 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3a44e6f new=com.google.android.velvet.VelvetApplication@3a44e6f
,08-24 16:36:08.168  1855  3929 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-24 16:36:08.183  1855  3929 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 16:36:08.184  1855  3929 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 16:36:08.184  1855  3929 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 16:36:08.184  1855  3929 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-24 16:36:08.185  3509  3932 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-24 16:36:08.189  3509  3932 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 16:36:08.189  3509  3932 E AndroidRuntime: Process: android.process.acore, PID: 3509
08-24 16:36:08.189  3509  3932 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:36:08.189  3509  3932 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:36:08.192   871  3958 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:36:08.192   871  3958 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:36:08.192   871  3958 E DropBoxManagerService: 	... 5 more
,08-24 16:36:08.243  1931  1931 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-24 16:36:08.266  1744  3960 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-24 16:36:08.267  1744  3960 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-24 16:36:08.304   871   889 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +140ms
,08-24 16:36:08.369   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-24 16:36:08.369   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-24 16:36:08.369   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-24 16:36:08.369   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-24 16:36:08.369   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-24 16:36:08.369   281   281 E qdoverlay: MdpCtrl close error in unset

```
