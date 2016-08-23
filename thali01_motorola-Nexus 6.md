#### Test 79763830b1f5deb_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-23 17:04:09.605  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 17:04:09.617  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 17:04:09.621  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 17:04:09.688  1517  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 17:04:09.688  1517  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 17:04:09.689  1517  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:04:09.689  1517  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-23 17:04:09.728  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 17:04:09.729  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 17:04:09.729  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-23 17:04:10.241  3770  3770 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 17:04:10.246  3770  3770 D AndroidRuntime: CheckJNI is OFF
08-23 17:04:10.288  3770  3770 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 17:04:10.340  3770  3770 I Radio-JNI: register_android_hardware_Radio DONE
08-23 17:04:10.361  3770  3770 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 17:04:10.365   874   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 17:04:10.388  2033  2052 W SearchService: Abort, client detached.
08-23 17:04:10.399  2033  2315 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c6f6fbb
08-23 17:04:10.399  2033  2336 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 17:04:10.399  2033  2033 I HotwordDetector: Closing mic
08-23 17:04:10.410  3770  3770 D AndroidRuntime: Shutting down VM
08-23 17:04:10.423   874   885 I ActivityManager: Start proc 3779:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 17:04:10.457   376  2339 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 17:04:10.458   376  2339 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 17:04:10.467   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 17:04:10.468  2033  2324 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 17:04:10.469  2033  2332 I MicroRecognitionRnrImpl: Detection finished
08-23 17:04:10.497  3779  3779 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 17:04:10.518  3779  3779 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 17:04:10.525  3779  3779 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 294-296)
08-23 17:04:10.525  3779  3779 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 17:04:10.542  3779  3779 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {20bb1de}
08-23 17:04:10.543  3779  3779 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 17:04:10.543  3779  3779 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 17:04:10.552  3779  3779 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 17:04:10.553  3779  3779 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 17:04:10.572  3779  3779 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 17:04:10.583  3779  3779 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 17:04:10.583  3779  3779 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 17:04:10.583  3779  3779 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 17:04:10.583  3779  3779 I Adreno  : Build Date                       : 10/20/15
08-23 17:04:10.583  3779  3779 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 17:04:10.583  3779  3779 I Adreno  : Local Branch                     : M14
08-23 17:04:10.583  3779  3779 I Adreno  : Remote Branch                    : 
08-23 17:04:10.583  3779  3779 I Adreno  : Remote Branch                    : 
08-23 17:04:10.583  3779  3779 I Adreno  : Reconstruct Branch               : 
08-23 17:04:10.656   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14e9594:true
,08-23 17:04:10.703  3779  3779 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 17:04:10.719  3779  3779 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 17:04:10.784  3779  3818 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 17:04:10.794  3779  3804 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 17:04:10.821  3779  3818 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 17:04:10.890   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +479ms
,08-23 17:04:10.898  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-23 17:04:10.969  3779  3779 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3779
,08-23 17:04:11.126  3779  3779 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 17:04:11.220   874  1977 I ActivityManager: Killing 3198:com.google.android.gm/u0a78 (adj 15): empty #17
,08-23 17:04:11.275   874  1977 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-23 17:04:11.369  3779  3820 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1696929488
,08-23 17:04:11.374  3779  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 17:04:11.374  3779  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 17:04:11.374  3779  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 17:04:11.374  3779  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 17:04:11.374  3779  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 17:04:11.374  3779  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6be2f02 added. We now have 1 listener(s)
,08-23 17:04:11.377  3779  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 17:04:11.377  3779  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 17:04:11.378  3779  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 17:04:11.378  3779  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 17:04:11.381  3779  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fadc49 added. We now have 1 listener(s)
,08-23 17:04:11.381  3779  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 17:04:11.383   874  1315 D WifiService: New client listening to asynchronous messages
08-23 17:04:11.384  3779  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 17:04:11.384  3779  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 17:04:11.384  3779  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 17:04:11.384  3779  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-23 17:04:11.384  3779  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 17:04:11.386  3779  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 17:04:11.386  3779  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 17:04:11.390  3779  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 17:04:11.390  3779  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 17:04:11.390  3779  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 17:04:11.390  3779  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 17:04:11.391  3779  3820 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 17:04:11.465  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 17:04:11.467  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 17:04:11.468  3779  3779 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 17:04:12.279  3779  3828 W jxcore-log: Initializing JXcore engine
,08-23 17:04:12.279  3779  3828 W jxcore-log: JXcore engine is ready
,08-23 17:04:12.319  3828  3828 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 17:04:12.319  3828  3828 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12719]" dev="sockfs" ino=12719 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 17:04:12.319  3828  3828 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 17:04:12.319  3828  3828 W Thread-326: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26739]" dev="sockfs" ino=26739 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 17:04:12.336  3779  3828 W jxcore-log: Starting JXcore engine
,08-23 17:04:12.419  3779  3828 W jxcore-log: Platform android
08-23 17:04:12.419  3779  3828 W jxcore-log: 
08-23 17:04:12.419  3779  3828 W jxcore-log: Process ARCH arm
08-23 17:04:12.419  3779  3828 W jxcore-log: 
,08-23 17:04:12.669  3779  3828 I jxcore-log: JXcore Cordova bridge is ready!
08-23 17:04:12.669  3779  3828 I jxcore-log: 
,08-23 17:04:12.669  3779  3828 W jxcore-log: JXcore engine is started
,08-23 17:04:12.676  3779  3820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 17:04:12.685  3779  3779 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 17:04:12.820   874  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 17:04:19.304  3038  3836 V KeepSync: Connecting to GoogleApiClient
,08-23 17:04:19.305   874  2303 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 17:04:19.363  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:19.366  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:19.399  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 17:04:19.399  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-23 17:04:19.399  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:04:19.400  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:19.423  1709  3837 V BaseAuthAsyncOperation: access token request failed
,08-23 17:04:19.424  3038  3836 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 17:04:19.498  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 17:04:19.498  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 17:04:19.498  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:04:19.498  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:19.529  3038  3836 E KeepSync: IOException
08-23 17:04:19.529  3038  3836 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 17:04:19.529  3038  3836 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 17:04:19.529  3038  3836 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 17:04:19.529  3038  3836 E KeepSync: 	... 10 more
,08-23 17:04:19.529  3038  3836 W KeepSync: Sync result 2
,08-23 17:04:19.545   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 128931, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:04:22.982  3779  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 17:04:22.982  3779  3828 I jxcore-log: 
,08-23 17:04:22.985  3779  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 17:04:22.985  3779  3828 I jxcore-log: 
,08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 17:04:22.994  3779  3828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 17:04:23.001  3779  3828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 17:04:23.004  3779  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 17:04:23.004  3779  3828 I jxcore-log: 
08-23 17:04:23.006  3779  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 17:04:23.006  3779  3828 I jxcore-log: 
,08-23 17:04:23.640  3779  3828 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-23 17:04:23.640  3779  3828 I jxcore-log: Failed to execute UT.,
08-23 17:04:23.640  3779  3828 I jxcore-log: 
08-23 17:04:23.642  3779  3828 I jxcore-log: Unit Test app is loaded,
08-23 17:04:23.642  3779  3828 I jxcore-log: 
,08-23 17:04:23.646  3779  3828 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 17:04:23.646  3779  3828 I jxcore-log: 
,08-23 17:04:23.651  3779  3828 I jxcore-log: My device name is: motorola-Nexus 6
08-23 17:04:23.651  3779  3828 I jxcore-log: 
,08-23 17:04:23.653  3779  3828 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 17:04:23.653  3779  3828 I jxcore-log: 
,08-23 17:04:23.668  3779  3779 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-23 17:04:27.984  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 17:04:27.984  3779  3828 I jxcore-log: 
,08-23 17:04:29.086  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 17:04:29.086  3779  3828 I jxcore-log: 
,08-23 17:04:29.136  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 17:04:29.136  3779  3828 I jxcore-log: 
,08-23 17:04:29.143  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 17:04:29.143  3779  3828 I jxcore-log: 
,08-23 17:04:29.167  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 17:04:29.167  3779  3828 I jxcore-log: 
,08-23 17:04:29.172  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 17:04:29.172  3779  3828 I jxcore-log: 
,08-23 17:04:29.983  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:29.998  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:30.002  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:30.056  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 17:04:30.056  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 17:04:30.056  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:04:30.056  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:30.093  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 17:04:30.093  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 17:04:30.095  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-23 17:04:32.613  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 17:04:32.613  3779  3828 I jxcore-log: 
,08-23 17:04:32.624  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 17:04:32.624  3779  3828 I jxcore-log: 
,08-23 17:04:32.632  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 17:04:32.632  3779  3828 I jxcore-log: 
,08-23 17:04:32.798  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 17:04:32.798  3779  3828 I jxcore-log: 
,08-23 17:04:33.641  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 17:04:33.641  3779  3828 I jxcore-log: 
,08-23 17:04:33.892  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 17:04:33.892  3779  3828 I jxcore-log: 
,08-23 17:04:33.898  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 17:04:33.898  3779  3828 I jxcore-log: 
,08-23 17:04:34.099  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 17:04:34.099  3779  3828 I jxcore-log: 
,08-23 17:04:34.120  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 17:04:34.120  3779  3828 I jxcore-log: 
,08-23 17:04:34.126  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 17:04:34.126  3779  3828 I jxcore-log: 
,08-23 17:04:34.132  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 17:04:34.132  3779  3828 I jxcore-log: 
,08-23 17:04:34.149  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-23 17:04:34.149  3779  3828 I jxcore-log: 
,08-23 17:04:34.169  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-23 17:04:34.169  3779  3828 I jxcore-log: 
,08-23 17:04:34.254  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 17:04:34.254  3779  3828 I jxcore-log: 
,08-23 17:04:34.260  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 17:04:34.260  3779  3828 I jxcore-log: 
,08-23 17:04:34.287  3779  3828 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 17:04:34.287  3779  3828 I jxcore-log: 
,08-23 17:04:34.300  3779  3828 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 17:04:34.301  3779  3828 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 17:04:34.301  3779  3828 I jxcore-log: 
,08-23 17:04:40.355   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-23 17:04:40.367  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-23 17:04:40.378   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 17:04:40.378   874   894 I Adreno  : Build Date                       : 10/20/15
08-23 17:04:40.378   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 17:04:40.378   874   894 I Adreno  : Local Branch                     : M14
08-23 17:04:40.378   874   894 I Adreno  : Remote Branch                    : 
08-23 17:04:40.378   874   894 I Adreno  : Remote Branch                    : 
08-23 17:04:40.378   874   894 I Adreno  : Reconstruct Branch               : 
,08-23 17:04:40.420   280   359 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (726 us)
,08-23 17:04:41.111  3779  3779 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 17:04:41.111  3779  3779 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 17:04:41.149   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-23 17:04:41.150  3779  3779 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ab42b24 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@535aba2, 16908290=android.view.AbsSavedState$1@535aba2}, android:focusedViewId=100}]}]
,08-23 17:04:41.150  3779  3779 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-23 17:04:41.153  3779  3779 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 17:04:41.154  3779  3779 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 17:04:41.169   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-23 17:04:41.173   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-23 17:04:41.181   874   883 I art     : Background partial concurrent mark sweep GC freed 47800(3MB) AllocSpace objects, 18(496KB) LOS objects, 33% free, 29MB/43MB, paused 1.464ms total 100.751ms
,08-23 17:04:41.185   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-23 17:04:41.185   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-23 17:04:41.419   280   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 17:04:41.425   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-23 17:04:41.431   874  1341 D SurfaceControl: Excessive delay in setPowerMode(): 258ms
,08-23 17:04:41.436   874   894 I DreamManagerService: Entering dreamland.
,08-23 17:04:41.437   874   894 I PowerManagerService: Dozing...
,08-23 17:04:41.439   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-23 17:04:41.496   376  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-23 17:04:41.496   376  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-23 17:04:41.517   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 17:04:41.525  1951  3847 D NfcService: Discovery configuration equal, not updating.
,08-23 17:04:41.545   874  1314 E native  : do suspend false
,08-23 17:04:41.569   874  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 17:04:41.587   874  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 17:04:41.603   874  1314 E native  : do suspend true
,08-23 17:04:41.634   376  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-23 17:04:41.634   376  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-23 17:04:42.025   874  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-23 17:04:47.338  1907  2659 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 17:04:50.238  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:50.428  1517  3853 I VacuumService: Vacuum at: now=1471964690428 tag=VacuumService
,08-23 17:04:50.445  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:50.458  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:50.460  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:04:50.492  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 17:04:50.493  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 17:04:50.493  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:04:50.493  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:50.535  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 17:04:50.535  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 17:04:50.535  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-23 17:04:50.576  1517  3854 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-23 17:04:50.578  1517  3854 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 17:04:50.603  1517  3854 W Uploader:  no longer exists, so no auth token.
,08-23 17:04:51.505  1517  3854 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-23 17:04:51.506  1517  3854 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-23 17:04:51.506  1517  3854 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:04:51.506  1517  3854 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:51.536  1517  3854 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 17:04:51.536  1517  3854 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 17:04:51.536  1517  3854 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 17:04:51.939  1517  3854 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-23 17:04:51.939  1517  3854 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-23 17:04:51.940  1517  3854 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:04:51.940  1517  3854 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:51.973  1517  3854 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 17:04:51.973  1517  3854 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 17:04:51.973  1517  3854 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 17:04:52.115  3728  3864 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 17:04:52.148  3728  3865 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 17:04:52.203  1517  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 17:04:52.204  1517  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 17:04:52.204  1517  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:04:52.204  1517  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:52.299  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-23 17:04:52.299  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 17:04:52.299  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:04:52.299  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:52.324  3728  3865 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 17:04:52.326  3728  3864 E BooksSync: Soft error
08-23 17:04:52.326  3728  3864 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:04:52.326  3728  3864 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 17:04:52.327  3728  3864 E BooksSync: Sync error
08-23 17:04:52.327  3728  3864 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:04:52.327  3728  3864 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 17:04:52.327  3728  3864 I BooksSync: Finished books sync
,08-23 17:04:52.335   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161796, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:04:52.573  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 17:04:52.573  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 17:04:52.573  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:04:52.573  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:52.593  3533  3867 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 17:04:52.593  3533  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jdm.a(PG:82)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jcs.o(PG:406)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jcn.a(PG:1379)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jcs.i(PG:143)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at blb.a(PG:3937)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at czp.a(PG:18188)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at czp.a(PG:9081)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at czq.run(PG:1686)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:04:52.593  3533  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jdj.a(PG:4091)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jdj.a(PG:1125)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jdm.a(PG:77)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	... 12 more
08-23 17:04:52.593  3533  3867 E HttpOperation: Caused by: faj: BadAuthentication
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at fal.a(PG:38)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	at jdj.a(PG:4089)
08-23 17:04:52.593  3533  3867 E HttpOperation: 	... 14 more
,08-23 17:04:52.676  1517  1990 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 17:04:52.676  1517  1990 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 17:04:52.676  1517  1990 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:04:52.676  1517  1990 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:52.694  3533  3867 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 17:04:52.694  3533  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jdm.a(PG:82)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jcs.o(PG:406)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jcn.a(PG:1379)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jcs.i(PG:143)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at hec.a(PG:42)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at hee.a(PG:102)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at czr.a(PG:65)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at kka.a(PG:108)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at czp.a(PG:19176)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at czp.a(PG:9081)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at czq.run(PG:1686)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:04:52.694  3533  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jdj.a(PG:4091)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jdj.a(PG:1125)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jdm.a(PG:77)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	... 15 more
08-23 17:04:52.694  3533  3867 E HttpOperation: Caused by: faj: BadAuthentication
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at fal.a(PG:38)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	at jdj.a(PG:4089)
08-23 17:04:52.694  3533  3867 E HttpOperation: 	... 17 more
08-23 17:04:52.694  3533  3867 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 17:04:52.694  3533  3867 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at hec.a(PG:42)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at hee.a(PG:102)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at czr.a(PG:65)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at kka.a(PG:108)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	... 15 more
08-23 17:04:52.694  3533  3867 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at fal.a(PG:38)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 17:04:52.694  3533  3867 E ExperimentLoader: 	... 17 more
,08-23 17:04:52.699  1517  3854 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-23 17:04:52.700  1517  3854 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-23 17:04:52.700  1517  3854 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:04:52.700  1517  3854 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:04:52.733  1517  3854 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
08-23 17:04:52.733  1517  3854 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 17:04:52.733  1517  3854 E Uploader: ,	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 17:04:52.733  1517  3854 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 17:04:52.833   874  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-23 17:04:52.842   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 162023, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:04:55.639   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 17:04:58.134  1517  2055 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 17:05:11.926  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:05:11.939  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:05:11.944  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:05:11.997  1517  2986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 17:05:11.997  1517  2986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 17:05:11.997  1517  2986 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:05:11.997  1517  2986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:05:12.049  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 17:05:12.050  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 17:05:12.050  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-23 17:05:32.732   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:05:40.408  1873  1926 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-23 17:05:40.408  1873  1926 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-23 17:05:40.439  1517  1517 I ConfigService: onCreate
,08-23 17:05:45.472  1517  1517 I ConfigService: onDestroy
,08-23 17:05:52.833  1517  3854 D Uploader: Network request failed class java.net.SocketTimeoutException(timeout)
,08-23 17:05:57.852   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 17:06:13.959   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=243730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:06:26.632  3038  3877 V KeepSync: Connecting to GoogleApiClient
,08-23 17:06:26.633   874  1945 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 17:06:26.699  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:06:26.703  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:06:26.748  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-23 17:06:26.749  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-23 17:06:26.749  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:06:26.749  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:06:26.776  1709  3878 V BaseAuthAsyncOperation: access token request failed
,08-23 17:06:26.779  3038  3877 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 17:06:26.888  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 17:06:26.889  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 17:06:26.898  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:06:26.898  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:06:26.922  3038  3877 E KeepSync: IOException
08-23 17:06:26.922  3038  3877 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 17:06:26.922  3038  3877 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 17:06:26.922  3038  3877 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 17:06:26.922  3038  3877 E KeepSync: 	... 10 more
08-23 17:06:26.922  3038  3877 W KeepSync: Sync result 2
,08-23 17:06:26.929   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 256233, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:06:35.792   874   885 I ActivityManager: Start proc 3879:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-23 17:06:35.844  3879  3879 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-23 17:06:35.922  3879  3891 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-23 17:06:36.029  3879  3891 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-23 17:06:36.080  3879  3891 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 17:06:36.160  3879  3879 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-23 17:06:36.347  3906  3906 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-619299773.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-619299773.dex
,08-23 17:06:36.409  3879  3879 W InstanceID/Rpc: Found 10011
,08-23 17:06:36.525   874   884 I ActivityManager: Killing 3369:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 17:06:36.590  3906  3906 I dex2oat : dex2oat took 250.012ms (threads: 4) arena alloc=143KB java alloc=29KB native alloc=1259KB free=1300KB
,08-23 17:06:38.066   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 17:06:57.747   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:07:03.434  3728  3966 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 17:07:03.463  3728  3967 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 17:07:03.473  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:03.477  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:03.509  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 17:07:03.510  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 17:07:03.510  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:07:03.510  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:07:03.542  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:03.544  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:03.571  1517  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-23 17:07:03.572  1517  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 17:07:03.572  1517  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:07:03.572  1517  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:07:03.589  3728  3967 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 17:07:03.590  3728  3966 E BooksSync: Soft error
08-23 17:07:03.590  3728  3966 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:07:03.590  3728  3966 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 17:07:03.590  3728  3966 E BooksSync: Sync error
08-23 17:07:03.590  3728  3966 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:07:03.590  3728  3966 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 17:07:03.591  3728  3966 I BooksSync: Finished books sync
,08-23 17:07:03.605   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 293119, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:07:34.004  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:34.006  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:34.050  1517  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-23 17:07:34.050  1517  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 17:07:34.050  1517  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:07:34.050  1517  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:07:34.073  3533  3972 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 17:07:34.073  3533  3972 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jdm.a(PG:82)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jcs.o(PG:406)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jcn.a(PG:1379)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jcs.i(PG:143)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at blb.a(PG:3937)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at czp.a(PG:18188)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at czp.a(PG:9081)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at czq.run(PG:1686)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:07:34.073  3533  3972 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jdj.a(PG:4091)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jdj.a(PG:1125)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jdm.a(PG:77)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	... 12 more
08-23 17:07:34.073  3533  3972 E HttpOperation: Caused by: faj: BadAuthentication
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at fal.a(PG:38)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	at jdj.a(PG:4089)
08-23 17:07:34.073  3533  3972 E HttpOperation: 	... 14 more
,08-23 17:07:34.144  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 17:07:34.144  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 17:07:34.144  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:07:34.144  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:07:34.178  3533  3972 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 17:07:34.178  3533  3972 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jdm.a(PG:82)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jcs.o(PG:406)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jcn.a(PG:1379)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jcs.i(PG:143)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at hec.a(PG:42)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at hee.a(PG:102)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at czr.a(PG:65)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at kka.a(PG:108)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at czp.a(PG:19176)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at czp.a(PG:9081)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at czq.run(PG:1686)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:07:34.178  3533  3972 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jdj.a(PG:4091)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jdj.a(PG:1125)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jdm.a(PG:77)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	... 15 more
08-23 17:07:34.178  3533  3972 E HttpOperation: Caused by: faj: BadAuthentication
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at fal.a(PG:38)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	at jdj.a(PG:4089)
08-23 17:07:34.178  3533  3972 E HttpOperation: 	... 17 more
,08-23 17:07:34.178  3533  3972 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
08-23 17:07:34.178  3533  3972 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at hec.a(PG:42)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at hee.a(PG:102)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at czr.a(PG:65)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at kka.a(PG:108)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	... 15 more
08-23 17:07:34.178  3533  3972 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at fal.a(PG:38)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 17:07:34.178  3533  3972 E ExperimentLoader: 	... 17 more
,08-23 17:07:34.332   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 294150, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:07:34.893   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 17:07:36.674   874  1988 I ActivityManager: Start proc 3974:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-23 17:07:36.747  3974  3974 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-23 17:07:36.805  3974  3974 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-23 17:07:36.856  3974  3997 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 17:07:36.889  1517  1990 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 17:07:36.889  1517  1990 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-23 17:07:36.889  1517  1990 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:07:36.890  1517  1990 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:07:36.904  3974  3997 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 17:07:36.905  3974  3997 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 17:07:36.912   874  1487 I ActivityManager: Killing 2250:com.google.android.talk/u0a61 (adj 15): empty #17
,08-23 17:07:52.992  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:53.003  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:53.007  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:07:53.058  1517  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 17:07:53.058  1517  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 17:07:53.059  1517  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:07:53.059  1517  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:07:53.094  1517  2879 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 17:07:53.094  1517  2879 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 17:07:53.094  1517  2879 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 17:07:53.094  1517  2879 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-23 17:07:53.094  1517  2879 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-23 17:07:53.094  1517  2879 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-23 17:07:53.094  1517  2879 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 17:07:53.102  3496  3525 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 17:07:53.102  3496  3525 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-23 17:07:53.102  3496  3525 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-23 17:07:53.102  3496  3525 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-23 17:07:53.102  3496  3525 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-23 17:07:53.102  3496  3525 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-23 17:07:53.102  3496  3525 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 17:08:07.154  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:08:07.156  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:08:07.169  3974  4003 V GoogleAuthProtoRequest: [322] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 17:08:07.213  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 17:08:07.213  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 17:08:07.213  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:08:07.213  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:08:07.241  3974  4003 W ExperimentUpdateService: [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 17:08:07.242  3974  4003 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 17:08:14.439   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=364210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:08:34.719   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 17:08:55.772   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:09:07.456  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:09:07.458  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:09:07.478  3974  4006 V GoogleAuthProtoRequest: [323] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 17:09:07.503  1517  2986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 17:09:07.503  1517  2986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-23 17:09:07.503  1517  2986 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:09:07.503  1517  2986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 17:09:07.520  3974  4006 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 17:10:41.024  3038  4013 V KeepSync: Connecting to GoogleApiClient
,08-23 17:10:41.024   874  1974 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 17:10:41.073  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:10:41.075  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:10:41.103  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 17:10:41.103  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 17:10:41.104  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:10:41.104  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:10:41.124  1709  4014 V BaseAuthAsyncOperation: access token request failed,
,08-23 17:10:41.125  3038  4013 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 17:10:41.187  1517  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 17:10:41.187  1517  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 17:10:41.187  1517  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:10:41.187  1517  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:10:41.206  3038  4013 E KeepSync: IOException
08-23 17:10:41.206  3038  4013 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 17:10:41.206  3038  4013 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 17:10:41.206  3038  4013 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 17:10:41.206  3038  4013 E KeepSync: 	... 10 more
,08-23 17:10:41.206  3038  4013 W KeepSync: Sync result 2
,08-23 17:10:41.216   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 510533, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:11:07.722  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:07.724  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:07.738  3974  4016 V GoogleAuthProtoRequest: [324] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 17:11:07.760  1517  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-23 17:11:07.760  1517  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 17:11:07.760  1517  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:11:07.760  1517  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 17:11:07.779  3974  4016 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 17:11:25.739  3728  4018 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 17:11:25.777  3728  4019 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 17:11:25.790  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:25.792  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:25.818  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 17:11:25.819  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 17:11:25.819  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:11:25.819  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:11:25.849  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:25.854  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:25.894  1517  2986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 17:11:25.894  1517  2986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 17:11:25.895  1517  2986 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:11:25.895  1517  2986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:11:25.922  3728  4019 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:11:25.923  3728  4018 E BooksSync: Soft error
08-23 17:11:25.923  3728  4018 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:11:25.923  3728  4018 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 17:11:25.924  3728  4018 E BooksSync: Sync error
08-23 17:11:25.924  3728  4018 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 17:11:25.924  3728  4018 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 17:11:25.924  3728  4018 I BooksSync: Finished books sync
,08-23 17:11:25.939   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 555401, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:11:57.702  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:57.704  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:11:57.746  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 17:11:57.746  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.,
,08-23 17:11:57.746  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:11:57.746  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:11:57.775  3533  4022 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 17:11:57.775  3533  4022 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jdm.a(PG:82)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jcs.o(PG:406)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jcn.a(PG:1379)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jcs.i(PG:143)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at blb.a(PG:3937)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at czp.a(PG:18188)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at czp.a(PG:9081)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at czq.run(PG:1686)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:11:57.775  3533  4022 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jdj.a(PG:4091)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jdj.a(PG:1125)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jdm.a(PG:77)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	... 12 more
08-23 17:11:57.775  3533  4022 E HttpOperation: Caused by: faj: BadAuthentication
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at fal.a(PG:38)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	at jdj.a(PG:4089)
08-23 17:11:57.775  3533  4022 E HttpOperation: 	... 14 more
,08-23 17:11:57.825  1517  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 17:11:57.825  1517  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 17:11:57.825  1517  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 17:11:57.825  1517  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:11:57.840  3533  4022 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 17:11:57.840  3533  4022 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jdm.a(PG:82)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jcs.o(PG:406)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jcn.a(PG:1379)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jcs.i(PG:143)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at hec.a(PG:42)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at hee.a(PG:102)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at czr.a(PG:65)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at kka.a(PG:108)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at czp.a(PG:19176)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at czp.a(PG:9081)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at czq.run(PG:1686)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:11:57.840  3533  4022 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jdj.a(PG:4091)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jdj.a(PG:1125)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jdm.a(PG:77)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	... 15 more
08-23 17:11:57.840  3533  4022 E HttpOperation: Caused by: faj: BadAuthentication
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at fal.a(PG:38)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	at jdj.a(PG:4089)
08-23 17:11:57.840  3533  4022 E HttpOperation: 	... 17 more
08-23 17:11:57.840  3533  4022 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 17:11:57.840  3533  4022 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at hec.a(PG:42)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at hee.a(PG:102)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at czr.a(PG:65)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at kka.a(PG:108)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	... 15 more
08-23 17:11:57.840  3533  4022 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at fal.a(PG:38)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 17:11:57.840  3533  4022 E ExperimentLoader: 	... 17 more
,08-23 17:11:57.972   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 587176, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 17:11:58.573   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=588344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 17:12:19.612   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=609384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:12:58.426   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=648197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 17:13:19.506   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=669277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:15:07.971  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:15:07.973  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:15:07.988  3974  4038 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 17:15:08.025  1517  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 17:15:08.025  1517  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 17:15:08.025  1517  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:15:08.025  1517  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 17:15:08.039  3974  4038 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 17:22:12.546   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1202317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 17:22:16.879   874  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1206650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 17:22:29.052   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 17:23:08.221  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:23:08.223  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 17:23:08.235  3974  4065 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 17:23:08.263  1517  1990 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-23 17:23:08.264  1517  1990 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 17:23:08.264  1517  1990 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 17:23:08.264  1517  1990 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 17:23:08.303  3974  4065 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 17:23:08.304  3974  4065 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,TIME-OUT KILL (timeout was 1400000ms),08-23 17:27:41.338  4077  4077 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 17:27:41.342  4077  4077 D AndroidRuntime: CheckJNI is OFF
08-23 17:27:41.378  4077  4077 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 17:27:41.419  4077  4077 I Radio-JNI: register_android_hardware_Radio DONE
08-23 17:27:41.440  4077  4077 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 17:27:41.447   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-23 17:27:41.447   874   887 I ActivityManager: Killing 3779:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-23 17:27:41.562   874   897 W PackageSettings: Skipping PackageSetting{99793e5 com.example.hello/10273} due to missing metadata
08-23 17:27:41.565   874  1977 I WindowState: WIN DEATH: Window{50c8bc4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 17:27:41.565   874  1315 D WifiService: Client connection lost with reason: 4
08-23 17:27:41.566   874  2233 D GraphicsStats: Buffer count: 2
08-23 17:27:41.598   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-23 17:27:41.598   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-23 17:27:41.599   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-23 17:27:41.599   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-23 17:27:41.599   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:27:41.599   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:41.599   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 17:27:41.599   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 17:27:41.600   874   887 I ActivityManager:   Force finishing activity ActivityRecord{22a4515 u0 com.test.thalitest/.MainActivity t2}
08-23 17:27:41.604   874   897 I art     : Starting a blocking GC Explicit
08-23 17:27:41.633   874  1974 W ActivityManager: Spurious death for ProcessRecord{7a4d635 0:com.test.thalitest/u0a0}, curProc for 3779: null
08-23 17:27:41.643   874   897 I art     : Explicit concurrent mark sweep GC freed 15745(1021KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 655us total 38.920ms
08-23 17:27:41.667   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-23 17:27:41.672  4077  4077 I art     : System.exit called, status: 0
08-23 17:27:41.672  4077  4077 I AndroidRuntime: VM exiting with result code 0.
08-23 17:27:41.673   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-23 17:27:41.707   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-23 17:27:41.711  2645  2645 D BluetoothMapAppObserver: onReceive
08-23 17:27:41.712  2645  2645 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 17:27:41.713  1907  2252 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 17:27:41.715  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
08-23 17:27:41.720   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 17:27:41.723  3615  3615 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-23 17:27:41.727  1873  4089 I Keyboard.Facilitator.DecoderInitializer: run()
08-23 17:27:41.729  1873  4089 I Decoder : createOrResetDecoder
08-23 17:27:41.755  1964  1964 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-23 17:27:41.757  1517  1517 I ConfigService: onCreate
08-23 17:27:41.777  3479  4094 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 17:27:41.805  3479  3493 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj98B76F969) - 
08-23 17:27:41.811   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 17:27:41.816  1873  4089 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-23 17:27:41.827  1983  2063 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-23 17:27:41.828   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-23 17:27:41.830   874   886 E PackageManager: Failed to write settings, restoring backup
08-23 17:27:41.830   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 17:27:41.830   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 17:27:41.830   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 17:27:41.830   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 17:27:41.830   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 17:27:41.830   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:27:41.830   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:41.830   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 17:27:41.830  3479  4094 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-23 17:27:41.831  3479  3493 I Process : Sending signal. PID: 3479 SIG: 9
08-23 17:27:41.838   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-23 17:27:41.838   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 17:27:41.838   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 17:27:41.838   874   887 E DropBoxManagerService: 	... 13 more
08-23 17:27:41.840   874  1422 I ActivityManager: Start proc 4097:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-23 17:27:41.840  1983  2063 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 17:27:41.840  1983  2063 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1983
08-23 17:27:41.840  1983  2063 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:41.840  1983  2063 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 17:27:41.842   874  1974 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 17:27:41.842   874  4103 E DropBoxManagerService: Can't write: system_app_crash
08-23 17:27:41.842   874  4103 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 17:27:41.842   874  4103 E DropBoxManagerService: 	... 5 more
08-23 17:27:41.847  1983  2063 I Process : Sending signal. PID: 1983 SIG: 9
08-23 17:27:41.853  1517  1517 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-23 17:27:41.855  1517  1517 D AndroidRuntime: Shutting down VM
08-23 17:27:41.856  1517  1517 E AndroidRuntime: FATAL EXCEPTION: main
08-23 17:27:41.856  1517  1517 E AndroidRuntime: Process: com.google.process.gapps, PID: 1517
08-23 17:27:41.856  1517  1517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 17:27:41.856  1517  1517 E AndroidRuntime: 	... 8 more
08-23 17:27:41.860   874  4111 E DropBoxManagerService: Can't write: system_app_crash
08-23 17:27:41.860   874  4111 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 17:27:41.860   874  4111 E DropBoxManagerService: 	... 5 more
08-23 17:27:41.861  1517  1517 I Process : Sending signal. PID: 1517 SIG: 9
08-23 17:27:41.878  1873  4089 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-23 17:27:41.880  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-23 17:27:41.880  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-23 17:27:41.882  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-23 17:27:41.882  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-23 17:27:41.882  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-23 17:27:41.882  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-23 17:27:41.883  1873  4089 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-23 17:27:41.883  1873  4089 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 17:27:41.883  1873  4089 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-23 17:27:41.884  1873  4089 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-23 17:27:41.884  1873  4089 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-23 17:27:41.884  1873  4089 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-23 17:27:41.907   874   885 I ActivityManager: Process android.process.acore (pid 3479) has died
08-23 17:27:41.907   874   885 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-23 17:27:41.939   874  1305 W InputDispatcher: channel '315f897 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-23 17:27:41.939   874  1305 E InputDispatcher: channel '315f897 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-23 17:27:41.940   874  2233 D GraphicsStats: Buffer count: 1
08-23 17:27:41.940   874  1974 I WindowState: WIN DEATH: Window{315f897 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-23 17:27:41.940   874  1974 W InputDispatcher: Attempted to unregister already unregistered input channel '315f897 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-23 17:27:41.941   874  1315 D WifiService: Client connection lost with reason: 4
08-23 17:27:41.941   874  1945 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1983) has died
08-23 17:27:41.942   874  1945 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-23 17:27:41.947   874  1392 I ActivityManager: Process com.google.process.gapps (pid 1517) has died
08-23 17:27:41.947   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-23 17:27:41.947   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-23 17:27:41.948   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-23 17:27:41.965  1709  1709 W RocketImpressions: ClearcutLogger connection suspended: 1
08-23 17:27:41.970   874  1392 I ActivityManager: Start proc 4115:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
08-23 17:27:42.006  4115  4115 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-23 17:27:42.008  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 17:27:42.008  1709  1709 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 17:27:42.016  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 17:27:42.016  1709  1709 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 17:27:42.026  1709  4130 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 17:27:42.045   874  2303 I ActivityManager: Start proc 4132:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-23 17:27:42.046  2033  4129 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 17:27:42.058  1709  4130 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-23 17:27:42.058  1709  4130 E AndroidRuntime: Process: com.google.android.gms, PID: 1709
08-23 17:27:42.058  1709  4130 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 17:27:42.058  1709  4130 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: Can't write: system_app_crash
08-23 17:27:42.061   874  4138 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 17:27:42.061   874  4138 E DropBoxManagerService: 	... 5 more
08-23 17:27:42.070  1709  4130 I Process : Sending signal. PID: 1709 SIG: 9
08-23 17:27:42.088  4115  4115 I MultiDex: VM with version 2.1.0 has multidex support
08-23 17:27:42.088  4115  4115 I MultiDex: install
08-23 17:27:42.088  4115  4115 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 17:27:42.093  2033  4129 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 17:27:42.103  4115  4115 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-23 17:27:42.106   278   278 E lowmemorykiller: Error writing /proc/1709/oom_score_adj; errno=22
08-23 17:27:42.118  2033  4129 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-23 17:27:42.118  2033  4129 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 17:27:42.118  2033  4129 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2033
08-23 17:27:42.118  2033  4129 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:42.118  2033  4129 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 17:27:42.120   874  2303 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-23 17:27:42.121   874  2303 I ActivityManager: Killing 2033:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-23 17:27:42.121   874  4145 E DropBoxManagerService: Can't write: system_app_crash
08-23 17:27:42.121   874  4145 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 17:27:42.121   874  4145 E DropBoxManagerService: 	... 5 more
08-23 17:27:42.136  4115  4115 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 17:27:42.139  4115  4115 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 17:27:42.139  4115  4115 D AndroidRuntime: Shutting down VM
08-23 17:27:42.140  4115  4115 E AndroidRuntime: FATAL EXCEPTION: main
08-23 17:27:42.140  4115  4115 E AndroidRuntime: Process: com.google.process.gapps, PID: 4115
08-23 17:27:42.140  4115  4115 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 17:27:42.140  4115  4115 E AndroidRuntime: 	... 10 more
08-23 17:27:42.166   280   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
